# Ex02 Time Table
## Name : T.Rishabh srivatsav
## Reg : 21224113001
## Date:

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
    <title>Document</title>
</head>
<link href="berry.css" rel="stylesheet"\>
<body>
    <center><img src="Screenshot 2025-03-13 084118.png" height="100px" width="500px" alt="something went wrong"/></center>
    <center><h3>SLOT TIME TABLE T.Rishabh srivatsav-21224113001</h3></center>
    <center><table border="6">
        <tr>
            <td bgcolor="Yellow">Day/Time</td>
            <th bgcolor="Yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
        </tr>
        <tr>
            <td bgcolor="Yellow">8-10</td>
            <td colspan="3" align="center" bgcolor="cyan">     FREE SLOT   </td>
            <td bgcolor="cyan">PHY</td>
            <td bgcolor="cyan">CHE</td>
        </tr> 
        <tr>
            <td bgcolor="Yellow">10-12</td>
            <td bgcolor="cyan">GER</td>
            <td bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan">FWAD</td>
            <td bgcolor="cyan">FWAD</td>
            <td bgcolor="cyan">PHY</td>
        </tr>
        <tr>
            <td bgcolor="Yellow">12-1</td>
            <td colspan="5" align="center" bgcolor="cyan">LUNCH</td>
        </tr>
        <tr>
            <td bgcolor="Yellow">1-3</td>
            <td colspan="2" align="center" bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan">MAT</td>
            <td bgcolor="cyan">MAT</td>
            <td bgcolor="cyan">SS</td>
        </tr>
        <tr>
            <td bgcolor="Yellow" >3-5</td>
            <td colspan="2" align="center"bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan">GER</td>
            <td bgcolor="cyan">CHE</td>
            <td bgcolor="cyan">FWAD</td>
        </tr>
    </table></center><br>


    <center><table border="4" id="borderstyle">
        <tr>
            <td colspan="1">S.NO</td>
            <td colspan="2" align="center" >  SUBJECT CODE   </td>
            <td colspan="4" align="center" >  SUBJECT NAME  </td>
        </tr>
        <tr>
            <td colspan="1">1.</td>
            <th colspan="2">19AI302</th>
            <th colspan="4">FUNDAMENTALS OF WEB</th>
        </tr>
        <tr>
            <td colspan="1">2.</td>
            <th colspan="2">19AI303</th>
            <th colspan="4">FUNDAMENTALS OF PYTHON</th>
        </tr>
        <tr>
            <td colspan="1">3.</td>
            <th colspan="2">19AI404</th>
            <th colspan="4">FUNDAMENTALS OF C PROGRAM</th>
        </tr>
        <tr>
            <td colspan="1">4.</td>
            <th colspan="2">19AI502</th>
            <th colspan="4">ARTIFICIAL INTELLIGENCE</th>
        </tr>
        <tr>
            <td colspan="1">5.</td>
            <th colspan="2">19AI503</th>
            <th colspan="4">FUNDAMENTALS OF WEB</th>
        </tr>

    </table></center>
</body>
</html>
```


## OUTPUT
<img width="1920" height="1140" alt="Screenshot 2026-04-29 115452" src="https://github.com/user-attachments/assets/dd3c9065-69dd-44de-95f2-75a9dc3711a4" />




## RESULT
The program creating slot timetable using basic HTML tags is executed successfully.
