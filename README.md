# Ex03 Time Table
## Date:19/11/2024

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
<<html>
<head>
<title>slot Timetable</title>    
</head>    
<body>
<center>
<img src="/static/image.png"height="100"width="540">
</center>
<br>
<table align="center"width="540" cellspacing="2" cellpadding="4"border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - SRISHA M (24901268)</b></caption>
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
<td>FUNDAMENTAL OF C PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>FUNDAMENTAL OF C PROGRAMMING</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>    
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PRINICIPLE OF CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td>STATSTICS AND NUMERICAL METHODS</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th> 
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>SOFT SKILLS</td>   
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th> 
<td>STATISTICS AND NUMERICAL METHODS</td> 
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATON</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>PRINICIPLES OF CHEMISTRY IN ENGINEERING</td>  
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. NO.</th>  
<th>subject Code</th>
<th>subject Name</th>  
</tr>   
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>    
<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>    
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>principles of chemistry in Engineering (CHE)</td>    
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>STATISTICS AND NUMERICAL METHODS (MAT)</td>    
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>Soft Skills</td>    
</tr>
</table>
</body>
</html>
```

## OUTPUT

![Screenshot 2024-11-17 120240](https://github.com/user-attachments/assets/74764f59-6f8c-4acc-a83d-5f95bbfa2e11)
## RESULT

The program for creating slot timetable using basic HTML tags is executed successfully.
