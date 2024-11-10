# Ex03 Slot-Time Table
## Date:10-11-2024

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

index.html

```
<html> 
<head> 
<title> Course Schedule </title> 
</head> 
<body> 
    <center>
<img src="logo.png" height="100" width="540"> 
</center>
<br> 
<table align="center" width="540" cellspacing="2" cellpadding="4" 
border="5" bgcolor="cyan"> 
<caption><b>SCHEDULE OF ALL COURSES</b></caption> 
<tr align="center"> 
<th bgcolor="yellow">Day/Time</th> 
<th bgcolor="yellow">Monday</th> 
<th bgcolor="yellow">Tuesday</th> 
<th bgcolor="yellow">Wednesday</th> 
<th bgcolor="yellow">Thursday</th> 
<th bgcolor="yellow">Friday</th> 
</tr> 
<tr align="center"> 
<th bgcolor="yellow">8-10</th> 
<td >FREE SLOT</td> 
<td>PYTHON PROGRAMMING</td> 
<td>FUNDAMENTALS OF WEB</td> 
<td>FREE SLOT</td> 
<td>PRALLEL COMPUTING ARCHITECTURE</td> 
</tr> 
<tr align="center"> 
<th bgcolor="yellow">10-12</th> 
<td>FREE SLOT</td> 
<td> FREE SLOT</td> 
<td>QUANTITATIVE ABILITY</td> 
<td>FREE SLOT</td> 
<td>TRANSFORMS AND ITS APPLICATION</td> 
</tr> 
<tr> 
<th bgcolor="yellow">12-1</th> 
<td colspan="5" align="center">L U N C H</td> 
</tr> 
<tr align="center"> 
<th bgcolor="yellow">1-3</th> 
<td >CHEMISTRY</td> 
<td>FREE SLOT</td> 
<td>MENTOR MEET</td> 
<td>FREE SLOT</td> 
<td>FREE SLOT</td>
</tr> 
<tr align="center"> 
<th bgcolor="yellow">3-5</th> 
<td>TRANSFORMS AND ITS APPLICATION</td> 
<td>PYTHON PROGRAMMING</td> 
<td>PYTHON PROGRAMMING</td> 
<td>DATA STRUCTURE</td> 
<td>DATA STRUCTURE</td> 
</tr> 
</table> 
<br> 
<table align="center" cellspacing="2" cellpadding="4" border="2"> 
<tr align="center"> 
<th>S. No.</th> 
<th>Subject Code</th> 
<th>Subject Name</th> 
<tr>
    <td align="center">1.</td> 
    <td align="center">19AI414</td> 
    <td>FUNDAMENTALS OF WEB (FWAD)</td>
</tr>
<tr><td align="center">2.</td> 
    <td align="center">19AI308</td> 
    <td>DATA STRUCTURE(C PROGRAM)</td> 
</tr>
<tr><td align="center">3.</td> 
    <td align="center">19EY710</td> 
    <td>QUANTITATIVE ABILITY</td> 
</tr>
<tr><td align="center">4.</td> 
    <td align="center">19CY205</td> 
    <td>PRINCIPLES OF CHEMISTRY (CHE)</td>
</tr>
<tr><td align="center">5.</td> 
    <td align="center">19MA219</td> 
    <td>TRANSFORMS AND ITS APPLICATION</td> 
</tr>
<tr><td align="center">6.</td> 
    <td align="center">19AI405</td> 
    <td>PRALLEL COMPUTING ARCHITECTURE</td> 
</tr>
</table> 
<center>
    <h2>
<caption><b>By MONISH N (212223240097)</b></caption>
</h2>
</center>
</body> 
</html>
```

## OUTPUT
![Screenshot (201)](https://github.com/user-attachments/assets/173b98d1-3e36-4563-9c77-c040bba050c6)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
