# Ex03 Time Table
## Date:30-03-2024

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
        <title>TIMETABLE</title>
        
    </head>
    <body>
        <center>
              <img src="/static/logo.png" width="600px">
              <h3>SLOT TIMETABLE - JAYAPRIYA T (212221220022)</h3>
        </center>
        <table border="5px" cellspacing="5px" cellpadding="5px" align="center">
            <tr>
                <th bgcolor="#ff6699">DAY/TIME</th>
                <th bgcolor="#ff6699">MONDAY</th>
                <th bgcolor="#ff6699">TUESDAY</th>
                <th bgcolor="#ff6699">WEDNESDAY</th>
                <th bgcolor="#ff6699">THURSDAY</th>
                <th bgcolor="#ff6699">FRIDAY</th>
            </tr>
            <tr>
                <th bgcolor="#00ffbf">8-10</th>
                <td bgcolor="#00ffff">FWAD</td>
                <td bgcolor="#00ffff">BSM</td>
                <td bgcolor="#00ffff">BSM</td>
                <td bgcolor="#00ffff">FREE SLOT</td>
                <td bgcolor="#00ffff">FREE SLOT</td>
            </tr>
            <tr>
                <th bgcolor="#00ffbf">10-12</th>
                <td bgcolor="#00ffff">FREE SLOT</td>
                <td bgcolor="#00ffff">BSM</td>
                <td bgcolor="#00ffff">GENDER</td>
                <td bgcolor="#00ffff">ADC</td>
                <td bgcolor="#00ffff">BSM</td>
            </tr>
            <tr>
                <th bgcolor="#00ffbf">12-1</th>
                <td colspan="5" align="center" bgcolor="#bfff00">LUNCH BREAK</td>
            </tr>
            <tr>
                <th bgcolor="#00ffbf">1-3</th>
                <td bgcolor="#00ffff">BSM</td>
                <td bgcolor="#00ffff">FWAD</td>
                <td bgcolor="#00ffff">GENDER</td>
                <td bgcolor="#00ffff">FREE SLOT</td>
                <td bgcolor="#00ffff">ADC</td>
            </tr>
            <tr>
                <th bgcolor="#00ffbf">3-5</th>
                <td bgcolor="#00ffff">ADC</td>
                <td bgcolor="#00ffff">FREE SLOT</td>
                <td bgcolor="#00ffff">PYTHON</td>
                <td bgcolor="#00ffff">FWAD</td>
                <td bgcolor="#00ffff">OPEN SOURCE OS</td>
            </tr>
            </table>
            <table>
            <br>
            <table border="5px" cellpadding="10px"  align="center" >
           <tr>
           <th bgcolor="#ff6699"> S.No </th>
             <th bgcolor="#ff6699"> SUBJECT CODE </th>
           <th bgcolor="#ff6699"> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td bgcolor="#ff6699"> 1. </td>
           <td bgcolor="#bfff00"> 19AI414 </td>
           <td bgcolor="#bfff00"> Fundamental of web application and development </td>
           </tr>
           <tr>
           <td bgcolor="#ff6699"> 2. </td>
           <td bgcolor="#bfff00">19IT405</td>
           <td bgcolor="#bfff00">  Data structures using python  </td>
           </tr>
           <tr>
           <td bgcolor="#ff6699"> 3. </td>
           <td bgcolor="#bfff00"> 19MD601</td> 
           <td bgcolor="#bfff00">Biomedical Sensors and Measurements  </td>
           </tr>
           <tr>
           <td bgcolor="#ff6699"> 4. </td>
           <td bgcolor="#bfff00"> 19CS545 </td>
           <td bgcolor="#bfff00"> Open Source Operating System </td>
           </tr>
           <tr>
           <td bgcolor="#ff6699"> 5. </td>
           <td bgcolor="#bfff00"> 19EN609 </td>
           <td bgcolor="#bfff00"> Gender Sensitization </td>
           </tr>
           <tr>
           <td bgcolor="#ff6699"> 6. </td>
           <td bgcolor="#bfff00"> 19EC306 </td>
           <td bgcolor="#bfff00"> Analog and Digital Communication </td>
           </tr>

        </table>

    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-03-30 190223-1.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
