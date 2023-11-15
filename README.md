# Ex03 Time Table
## Date:30.10.2023

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
     <title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width"550">
</center>
<br>
     <table align="center" width="550" cellspacing="2" cellpadding="4" border="5" bgcolor="orange">
     <caption><b>Time Table - DHARANI DHARAN G (23008869)</b></caption>
<tr align="center">
	<th bgcolor="cyan">Day/Time</th>
	<th bgcolor="cyan">Monday</th>
	<th bgcolor="cyan">Tuesday</th>
	<th bgcolor="cyan">Wednesday</th>
	<th bgcolor="cyan">Thursday</th>
 	<th bgcolor="cyan">Friday</th>
</tr>
<tr align="center">
	<th bgcolor="cyan">8-10</th>
	<td colspan="2">Free slot</td>
	<td>Web development</td>
	<td>C programming</td>
	<td>Calculus and matrices</td>
</tr>
<tr align="center">
	<th bgcolor="cyan">10-12</th>
	<td>Free slot</td>
	<td>Principles of chemistry in engineering</td>
	<td>Free slot</td>
	<td>Web development</td>
	<td>Physics in quantum computing</td>
</tr>
<tr>
	<th bgcolor="cyan">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="cyan">1-3</th>
	<td>Principles of chemistry in engineering</td>
	<td>Communicative English</td>
	<td>C programming</td>
	<td>Communicative English</td>
	<td>Web development</td>
</tr>
<tr align="center">
	<th bgcolor="cyan">3-5</th>
	<td>Physics in quantum computing</td>
	<td>Soft skills</td>
	<td>Free slot</td>
	<td>Calculus and matrices</td>
	<td>Free slot</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI304</td>
<td>C programming</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Web development</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CY205</td>
<td>Principles of chemistry in engineering</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EN101</td>
<td>Communicative English</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY701</td>
<td>Soft skills</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19MA201</td>
<td>Calculus and matrices</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19PH214</td>
<td>Physics in quantum computing</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![Screenshot 2023-11-15 133317](https://github.com/DHARANIDHARAN03K/slot/assets/144870858/21c0fbaf-2728-448e-84eb-f76caa119ed8)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
