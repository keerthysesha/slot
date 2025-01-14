# Ex03 Time Table
# Date : 05-10-2023

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

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
      
</head>
<body>

    <img src="sec logo.jpg" alt="SEC Logo" style="display: block; margin: 0 auto;" align="center">
    <br>

    <table cellspacing="7" bgcolor="aqua" border="2" align="center">
    <h2 align="center">SLOT TIME TABLE - KEERTHY S (212221040082)</h2>
        <tr bgcolor="yellow" align="center">
            <th>Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>

        </tr>
        <tr align="center">
            <th bgcolor="yellow">8:00 -10:00AM</th>
            <td>DAA</td>
            <td>FWAD</td>
            <td>MPMC</td>
            <td>FREE SLOT</td>
            <td>MPMC</td>
            <td>DS</td>

        </tr>
        <tr align="center">
            <th bgcolor="yellow">10:00 -12:00 AM</th>
            <td>FREE SLOT</td>
            <td>OS</td>
            <td>FREE SLOT</td>
            <td>ALGEBRA</td>
            <td>DAA</td>
            <td>CNS</td>
        </tr>
        <tr>
            <th bgcolor="yellow">12:00 - 1:00PM</th>
            <td colspan="6" align="center">LUNCH</td>

        </tr>
        <tr align="center">
            <th bgcolor="yellow">1:00 - 3:00PM</th>
            <td>MPMC</td>
            <td>ALGEBRA</td>
            <td colspan="4">FREE SLOT</td>

        </tr>
        <tr align="center">
            <th bgcolor="yellow">3:00 - 5:00PM</th>
            <td>CNS</td>
            <td>EES</td>
            <td>DS</td>
            <td>FWAD</td>
            <td>OS</td>
            <td>FWAD</td>

        </tr>
    </table>

    <br>

    <table border="1" align="center">
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
    <td>19CS402</td>
    <td>Design and Analysis of Algorithms(DAA)</td>
    </tr>
    <tr>
    <td>3.</td>
    <td>19EC408</td>
    <td>Microprocessor and Microcontroller (MPMC)</td>
    </tr>
    <tr>
    <td>4.</td>
    <td>19CS412</td>
    <td>Cryptography and Network Security (CNS)</td>
    </tr>
    <tr>
    <td>5.</td>
    <td>19CS405</td>
    <td>Operating System (OS)</td>
    </tr>
    <tr>
    <td>6.</td>
    <td>19EY705</td>
    <td>Employment Enhancement Skills (EES)</td>
    </tr>
    <tr>
    <td>7.</td>
    <td>19AI403</td>
    <td>Introduction to Data Science (DS)</td>
    </tr>
    <tr>
    <td>8.</td>
    <td>19MA212</td>
    <td>Algebra and Number Theory (ALGEBRA)</td>
    </tr>
    </table>


</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot 2023-10-05 154928.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
