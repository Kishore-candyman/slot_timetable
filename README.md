# Ex03 Time Table
## Date: 16-11-2024

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
<html>
    <head>
        <title>
            slot name
        </title>
    </head>
    <body  text="maroon">
        <center>
        <img src="\static\logo.png" height="100" width="800">
        
        <table border="3" cellpadding="10" cellspacing="10" width="2000" >
            <caption align="centre">slot time table-ODD JUNIOR</caption>
            <TR bgcolor="silver">
                <TH>-</TH>
                <TH>MONDAY</TH><TH>TUESDAY</TH><TH>WEDNESDAY</TH><TH>THURSDAY</TH><TH>FRIDAY</TH><TH>SATURDAY</TH>
            </TR>
            <tr>
                <td>8am</td>
                <td bgcolor="aqua">Digital electronic</td>
                <td>-</td>
                <td bgcolor="aqua">Engineering Design and Modeling</td>
                <td>-</td>
                <td bgcolor="aqua">Physics for Quantum Computing</td>
                <td>-</td>
            </tr>
            <tr>
                <td>9am</td>
                <td bgcolor="aqua">Digital electronic</td>
                <td>-</td>
                <td bgcolor="aqua">Engineering Design and Modeling</td>
                <td>-</td>
                <td bgcolor="aqua">Physics for Quantum Computing</td>
                <td>-</td>
            </tr>
            <tr>
                <td>10am</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
                <td bgcolor="aqua">Physics for Quantum Computing</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
                <td bgcolor="aqua">Principle of chemistry in Engineering</td>
                <td bgcolor="aqua">Environmental Science and Sustainability</td>
                <td bgcolor="aqua">Principle of chemistry in Engineering</td>
            </tr>
            <tr>
                <td>11am</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
                <td bgcolor="aqua">Physics for Quantum Computing</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
                <td bgcolor="aqua">Principle of chemistry in Engineering</td>
                <td bgcolor="aqua">Environmental Science and Sustainability</td>
                <td bgcolor="aqua">Principle of chemistry in Engineering</td>
            </tr>
            <tr>
                <td>12pm</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>1pm</td>
                <td bgcolor="aqua">Engineering Design and Modeling</td>
                <td bgcolor="aqua">Digital electronic</td>
                <td bgcolor="aqua">Mentor Meet</td>
                <td bgcolor="aqua">Python Programing</td>
                <td>-</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
            </tr>
            <tr>
                <td>2pm</td>
                <td bgcolor="aqua">Engineering Design and Modeling</td>
                <td bgcolor="aqua">Digital electronic</td>
                <td bgcolor="aqua">Mentor Meet</td>
                <td bgcolor="aqua">Python Programming</td>
                <td>-</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
            </tr>
            <tr>
                <td>3pm</td>
                <td>-</td>
                <td bgcolor="aqua">Python Programming</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>4pm</td>
                <td>-</td>
                <td bgcolor="aqua">Python Programming</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
            </tr>

        </table>
        <table border="5" cellpadding="5" cellspacing="5" width="1000">
            <tr>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td>19AI302</td>
                <td>Engineering Design and Modeling</td>
            </tr>
            <tr>
                <td>19AI414</td>
                <td>Fundamentals of Web Application and Development</td>
            </tr>
            <tr>
                <td>19CY205</td>
                <td>Principle of chemistry in Engineering</td>
            </tr>
            <tr>
                <td>19EE404</td>
                <td>Digital electronic</td>
            </tr>
            <tr>
                <td>ECA-M-SCOFT</td>
                <td>Menotr Meet</td>
            </tr>
            <tr>
                <td>SH3214</td>
                <td>Physics for Quantum Computing</td>
            </tr>
            <tr>
                <td>SH4801</td>
                <td>Environmental Science and Sustainability</td>
            </tr>
        </table>
    </center>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (15).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
