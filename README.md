# Ex04 Time Table
## Date:18.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
html
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table</title>
</head>

<body bgcolor="red" text="#FFFFFF">

    <center>
        <img src="./logo.png" alt="College Logo" width="400" height="100">

        <h1>SAVEETHA ENGINEERING COLLEGE</h1>
        <h2>SLOT TIME TABLE</h2>
    </center>

    <table border="1" align="center" cellpadding="15" cellspacing="0"
           bgcolor="orange">

        <tr bgcolor="aqua">
            <th>TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>

        <tr>
            <th bgcolor="#14532D">8:00 AM - 9:29 AM</th>
            <td>free</td>
            <td>Cds</td>
            <td>Fwad</td>
            <td>Free</td>
            <td>Free</td>
            <td>pyt</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">9:45 AM - 11:15 AM</th>
            <td>Fwad</td>
            <td>Ca</td>
            <td>free</td>
            <td>pyt</td>
            <td>Free</td>
            <td>free</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">11:30 AM - 12:15 PM</th>
            <td>Free</td>
            <td>Free</td>
            <td>Mentor meet</td>
            <td>Mentor meet</td>
            <td>Free</td>
            <td>Mentor meet</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">12:15 PM - 12:59 PM</th>
            <td>Free</td>
            <td>Mentor meet</td>
            <td>Free</td>
            <td>Free</td>
            <td>Mentor meet</td>
            <td>Free</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">1:15 PM - 2:45 PM</th>
            <td>Free</td>
            <td>Fwad</td>
            <td>Free</td>
            <td>Jpl</td>
            <td>Free</td>
            <td>De</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">3:00 PM - 4:30 PM</th>
            <td>Free</td>
            <td>pyt</td>
            <td>Beee</td>
            <td>De</td>
            <td>Free</td>
            <td>Free</td>
        </tr>

    </table>

    <br>

    <center>
        <h2>SUBJECT DETAILS</h2>
    </center>

    <table border="1" align="center" cellpadding="10" cellspacing="0"
           bgcolor="blue">

        <tr bgcolor="pink">
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>

        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of web application (FWAD)</td>
        </tr>

        <tr>
            <td>2</td>
            <td>19EE305</td>
            <td> Basic EEE</td>
        </tr>

        <tr>
            <td>3</td>
            <td>19AI301</td>
            <td>Python programming (Pyt)</td>
        </tr>

        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>Digital electronics (De)</td>
        </tr>

        <tr>
            <td>5</td>
            <td>19CS305</td>
            <td>Computer architectutre (Ca)</td>
        </tr>

        <tr>
            <td>6</td>
            <td>19GE624</td>
            <td>Japanese Language N5 basics (Jpl)</td>
        </tr>
        <tr>
            <td>7</td>
            <td>19EY708</td>
            <td>Career development skills (Cds)</td>
        </tr>

    </table>

</body>
</html>



```

## OUTPUT
![alt text](<Screenshot 2026-11-18 225423.png>)

![alt text](<Screenshot 2026-11-18 223038.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
