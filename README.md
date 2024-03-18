# Ex03 Time Table
## Date:18/03/2024

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
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<table border="3" cellspacing="6" cellpading="6">
<caption>SLOT TIMETABLE FOR EVEN SEM : HEMANTH KUMAR.R(212223040065)</caption>
<tr>
<th bgcolor="gold">Day/Time</th>
<th bgcolor="gold">Monday</th>
<th bgcolor="gold">Tuesday</th>
<th bgcolor="gold">Wednesday</th>
<th bgcolor="gold">Thursday</th>
<th bgcolor="gold">Friday</th>
</tr>
<tr>0 
<td bgcolor="lightblue">8-10</td>
<td bgcolor="pink">BEEE</td>
<td bgcolor="pink">LEISURE</td>
<td bgcolor="pink">LEISURE</td>
<td bgcolor="pink">C PROGRAMMING</td>
<td bgcolor="pink">WEB APPLICATION</td>
</tr>
<tr>
<td bgcolor="cyan">10-12</td>
<td bgcolor="green">LEISURE</td>
<td bgcolor="green">C PROGRAMMING</td>
<td bgcolor="green">CN</td>
<td bgcolor="green">C PROGRAMMING</td>
<td bgcolor="green">LEISURE</td>
</tr>
<tr>
<td bgcolor="pink">12-1</td>
<td colspan="5" bgcolor="gold">_._._._._LUNCH BREAK_._._._._</td>
</tr>
<tr>
<td bgcolor="green">1-3</td>
<td bgcolor="lightblue">LOGIC AND COMBINATORICS</td>
<td bgcolor="lightblue">WEB APPLICATION</td>
<td bgcolor="lightblue">LEISURE</td>
<td bgcolor="lightblue">WEB APPLICATION</td>
<td bgcolor="lightblue">SOFT SKILL</td>
</tr>
<tr>
<td bgcolor="pink">3-5</td>
<td bgcolor="lightblue">LEISURE</td>
<td bgcolor="lightblue">LEISURE</td>
<td bgcolor="lightblue">LEISURE</td>
<td bgcolor="lightblue">OS</td>
<td bgcolor="lightblue">LOGIC AND COMBINATORICS</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19MA206</td>
<td>LOGIC AND COMBINATORICS</td>
</tr>
<tr>
<td>2.</td>
<td>19EY701</td>
<td>SOFT SKILL</td>
</tr>
<tr>
<td>3.</td>
<td>19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPEMENT</td>
</tr>
<tr>
<td>4.</td>
<td>19EE305</td>
<td>BEEE</td>
<tr>
<td>5.</td>
<td>19CS406</td>
<td>COMPUTER NETWORKS(CN)</td>
</tr>
<tr>
<td>6.</td>
<td>19CS405</td>
<td>OPERATING SYSTEM(OS)/td>
</tr>
<tr>
<td>7.</td>
<td>19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
</table>
</center>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-03-18 192044-1.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
