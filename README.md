Ex03 Time Table
Date:23-09-2025
AIM
To write a html webpage page to display your slot timetable.

ALGORITHM
STEP 1
Create a Django-admin Interface.

STEP 2
Create a static folder and inert HTML code.

STEP 3
Create a simple table using <table> tag in html.

STEP 4
Add header row using <th> tag.

STEP 5
Add your timetable using <td> tag.

STEP 6
Execute the program using runserver command.

PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - YOUR NAME</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - AKSHAYA SREE G</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>WEB</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>CE</td>
            <td>FREE SLOT</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td></td>
            <td>FWAD</td>
            <td></td>
            <td>CE</td>
            <td>CE</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>FREE SLOT</td>
            <td>CE</td>
            <td>WEB</td>
            <td>FREE SLOT</td>
            <td></td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>CE</td>
            <td>PY</td>
            <td></td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN612</td>
            <td>Communicative English (CE)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19PY206</td>
            <td>Pytthon Programming (PY)</td>
        </tr>
        
    </table>
</body>
</html>
```
OUTPUT
![alt text](<Screenshot 2025-09-23 103236.png>)

RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
