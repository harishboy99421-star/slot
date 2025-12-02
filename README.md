# Ex02 Time Table
## Date:

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
    <body>
        <center>
            <img src="image.png" width="400" heigth="100" align="middle">
        </center>
        <br>
        <table align="center" width="100" border="2" cellspacing="2" cellpadding="4">
            <caption><b>SLOT TIME TABLE - Harish(25019001)</b></caption>
            <tr bgcolor="yellow">
                <th>TIME/DAY</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
            </tr>
            <tr>
                <th bgcolor="lightyellow">8:00-10:00</th>
                <th>WEB DEVELOPMENT</th>
                <th>PYTHON PROGRAMMING</th>
                <th bgcolor="lightgreen">MODULE COMPLETION</th>
                <th bgcolor="lightblue">ASSESSMENT HOUR</th>
                <th bgcolor="lightgreen">MODULE COMPLETION</th>
            </tr>
            <tr>
                <th bgcolor="lightyellow">10:00-12:00</th>
                <th bgcolor="lightgreen">MODULE COMPLETION</th>
                <th>WEB DEVELOPMENT</th>
                <th>PYTHON PROGRAMMING</th>
                <th>ADVANCED C PROGRAMMING</th>
                <th>WEB DEVELOPMENT</th>
            </tr>
            <tr>
                <th bgcolor="lightyellow">12:00-1:00</th>
                <td colspan="5" align="center" bgcolor="pink"><b>LUNCH BREAK</b></td>
            </tr>
            <tr>
                <th bgcolor="lightyellow">1:00-3:00</th>
                <th>ARITIFICIAL INTELLIGENCE</th>
                <th>ADVANCED C PROGRAMMING</th>
                <th bgcolor="violet">MENTOR MEET</th>
                <th>ARITIFICIAL INTELLIGENCE</th>
                <th bgcolor="lightblue">ASSESSMENT HOUR</th>
            </tr>
        </table>
        <br>
        <table align="center" width="400" border="5" cellspacing="5" cellpadding="5">
            <tr>
                <th bgcolor="orange">S.No</th> 
                <th bgcolor="lightgreen">COURSE NAME</th>
                <th bgcolor="lightblue">COURSE CODE</th>
            </tr>
            <tr>
                <th>1</th> 
                <th>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</th>
                <th>19AI414</th>
            </tr>
            <tr>
                <th>2</th> 
                <th>FUNDAMENTALS OF ARITIFICIAL INTELLIGENCE</th>
                <th>19AI303</th>
            </tr>
            <tr>
                <th>3</th> 
                <th>FUNDAMENTALS OF PYTHON PROGRAMMING</th>
                <th>19AI301</th>
            </tr>
            <tr>
                <th>4</th> 
                <th>FUNDAMENTALS OF ADVANCED C PROGRAMMING</th>
                <th>19AI304</th>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f096ec28-b264-45e9-a840-c013614c4053" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
