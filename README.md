# Ex03 Time Table
## Date:22.4.2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <style>
        table {
            border: 3px solid black;
            width: 80%;
            height: 100px;
            border-collapse: collapse;
            margin: 10px auto;
        }

        th, td {
            border: 3px solid black;
            padding: 20px;
            text-align: center;
        }

        tr {
            background-color: #b3d9ff;
        }

        tr:nth-child(1) {
            background-color: #ff9999;
        }

        th {
            background-color: #ffccff;
        }
    </style>
</head>

<body>
    <table>
        <tr>
            <th>Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td>9-10</td>
            <td>Maths</td>
            <td>Physics</td>
            <td>Chemistry</td>
            <td>Biology</td>
            <td>English</td>
            <td>Free Slot</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td colspan="3" align="center">Lab Session</td>
            <td>Computer</td>
            <td>Biology</td>
            <td>Free Slot</td>
        </tr>
        <tr>
            <td>1-2</td>
            <td>English</td>
            <td>Maths</td>
            <td>Physics</td>
            <td>Chemistry</td>
            <td>Free Slot</td>
            <td>Seminar</td>
        </tr>
        <tr>
            <td>2-4</td>
            <td colspan="6" align="center">Project Work</td>
        </tr>
    </table>

    <table>
        <tr>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>20MA101</td>
            <td>Mathematics</td>
        </tr>
        <tr>
            <td>2</td>
            <td>20PH102</td>
            <td>Physics</td>
        </tr>
        <tr>
            <td>3</td>
            <td>20CH103</td>
            <td>Chemistry</td>
        </tr>
        <tr>
            <td>4</td>
            <td>20CS104</td>
            <td>Computer Science</td>
        </tr>
        <tr>
            <td>5</td>
            <td>20EN105</td>
            <td>English</td>
        </tr>
        <tr>
            <td>6</td>
            <td>20BI106</td>
            <td>Biology</td>
        </tr>
    </table>
</body>

</html>
```

## OUTPUT
![alt text](<Screenshot 2025-04-23 005804.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
