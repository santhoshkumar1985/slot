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
<html>
    <head>
        <title>timetable</title>
    </head>
    <body bgcolor="aqua">
        <img src="logo.png" height="155" width="1530" alt="error!" title="SEC logo">
        <h1 align="center"><b>FIRST SEMESTER TIMETABLE</b></h1>
        <h3 align="center"><b>SANTHOSH KUMAR K REF NO: 26019408</b></h3>
        <table border="6" cellspacing="5" cellpadding="8" align="center">
            <tr bgcolor="yellow" align="center">
                <th bgcolor="orange">day/time</th>
                <th>monday</th>
                <th>tuesday</th>
                <th>wednesday</th>
                <th>thursday</th>
                <th>friday</th>
                <th>saturday</th>
            </tr>
            <tr align="center">
                <td bgcolor="orange">8:00-9:30</td>
                <td>free</td>
                <td>cds</td>
                <td>fwad</td>
                <td>ca</td>
                <td>free</td>
                <td>pyt</td>        
            <tr align="center">
                <td bgcolor="orange">9:45-11:15</td>
                <td>fwad</td>
                <td>ca</td>
                <td>free</td>
                <td>pyt</td>
                <td colspan="2">free</td>
            </tr>
            <tr align="center">
                <td bgcolor="orange">11:30-12:15</td>
                <td>free</td>
                <td colspan="6">mentor meet</td>
            </tr>
            <tr align="center">
                <td bgcolor="orange">12:15-1:00</td>
                <td>mentor meet</td>
                <td colspan="5">free</td>
            </tr>
            <tr align="center">
                <td bgcolor="orange">1:15-2:45</td>
                <td>fwad</td>
                <td>de</td>
                <td colspan="3">free</td>
                <td>jpl</td>
            </tr>
            <tr align="center">
                <td bgcolor="orange">3:00-4:30</td>
                <td colspan="3">free</td>
                <td>beee</td>
                <td>pyt</td>
                <td>de</td>
            </tr>
           </table>       
           <br><br><table border="6" cellspacing="5" cellpadding="8" align="center">
            <tr bgcolor="red" align="center">
                <th>S.No</th>
                <th>subject code</th>
                <th>subject name</th>              
            </tr>
            <tr align="center">
                <td>1.</td>
                <td>19AI301</td>
                <td>Python Programming(pyt)</td>
            </tr>
            <tr align="center">
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(fwad)</td>
            </tr>
            <tr align="center">
                <td>3.</td>
                <td>19EY708</td>
                <td>Career Development Skills(cds)</td>
            </tr>
            <tr align="center">
                <td>4.</td>
                <td>19EE404</td>
                <td>Digital Electronics(de)</td>
            </tr>
             <tr align="center">
                <td>5.</td>
                <td>19CS305</td>
                <td>Computer Architecture(ca)</td>
            </tr>
            <tr align="center">
                <td>6.</td>
                <td>19EE305</td>
                <td>Basic Electrical, Electronics and Measurement Engineering(beee)</td>
            </tr>
            <tr align="center">
                <td>7.</td>
                <td>19GE624</td>
                <td>japanese Language N5 Basics(jpl)</td>
            </tr>
           </table>         
    </body>
</html>



```

## OUTPUT
![alt text](<Screenshot 2026-11-23 194146.png>)

![alt text](<Screenshot 2026-11-23 194156.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
