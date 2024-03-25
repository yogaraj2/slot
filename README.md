# Ex03 Time Table
## Date:25/03/24

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
        <title> MY SLOT </title>
    </head>
    <body >
        <center><img src="logo.png" width="700" height="100"> </center> 
    <center>
        <br>
        <CAPTION align="above"><b>SLOT TIMETABLE- YOGARAJ .S (212223040248)</b></CAPTION><br>
        <table border="5"  width="540"  cellspacing="5" cellpadding="10" >
            <tr align="center"  style="background-color: greenyellow;">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr align="center" style="background-color: cornflowerblue;">
                <th>8-10 </th>
                <th>FWAD</th>
                <th>BEEE</th>
                <th>CA</th>
                <th>OS</th>
                <th>BEEE</th>
                <th>CSC</th>
            </tr>
            <tr style="background-color: chartreuse;">
                <th align="center">10-12 </th>
                <th align="center">CE</th>
                <th align="center">CA</th>
                <th align="center"></th>
                <th align="center"></th>
                <th align="center">ML</th>
                <th align="center">ANT</th>
            </tr>
            <tr ALIGN="center" style="background-color: cyan;">
                <th>12-1 </th>
                <td colspan="6">LUNCH BREAK</td>
            </tr>
            <tr style="background-color: darkseagreen;">
                <th align="center">1-3 </th>
                <th align="center">ANT</th>
                <th align="center">OS</th>
                <th align="center">CE</th>
                <th align="center">FWAD</th>
                <th align="center">FWAD</th>
                <th align="center"></th>
            </tr>
            <tr style="background-color:blue;">
                <th align="center">3-5</th>
                <th align="center"></th>
                <th align="center">ML</th>
                <th align="center"></th>
                <th align="center"></th>
                <th align="center"></th>
                <th align="center"></th>
            </tr>
        </table>
        <br>
        <table border="5"  cellspacing="2" cellpadding="4"  >
           <b><tr >
                <th>S.NO.</th>
                <th>Subject Code</th>
                <th>subject Name</th>
            </tr>
            <tr align="center">
                <th>1</th>
                <th>19AI414</th>
                <th style="color:red">Fundamentals of Web Application Development(FWAD)</th>
            </tr>
            <tr align="center">
                <th>2</th>
                <th>19AI410</th>
                <th style="color:blue">Introduction To Machine Learning(ML)</th>
            </tr>
            <tr align="center">
                <th>3</th>
                <th>19CS305</th>
                <th style="color:green">Computer Architecture(CA)</th>
            </tr>
            <tr align="center">
                <th>4</th>
                <th>19CS405</th>
                <th style="color:crimson">Operating System(OS)</th>
            </tr>
            <tr align="center">
                <th>5</th>
                <th>19EE305</th>
                <th style="color:maroon">Basic Electrical,Electronics and Measurement Engineering(BEEE)</th>
            </tr>
            <tr align="center">
                <th>6</th>
                <th>19MA212</th>
                <th style="color:sienna">Algebra and Number Theory(ANT)</th>
            </tr>
            <tr align="center">
                <th>7</th>
                <th>19EN101</th>
                <th style="color:navy">Communicative English(CE)</th>
            </tr>
            <tr align="center">
                <th>8</th>
                <th>19EY702</th>
                <th style="color:gold">Creative Skills For Communication(CSC)</th>
            </b></tr>

        </table>
    </center>
    </body>
</html>
```

## OUTPUT

![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
