# Ex03 Time Table
## Date:30-12-2023

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
{% extends "timetable/base.html" %}
{% block title %}TIMETABLE App{% endblock %}
{% block content %}
	<H1><FONT COLOR="DARKCYAN"><CENTER>MY SLOT</FONT></H1>
	<table border="2" cellspacing="3" align="center">
	<tr>
	 <td align="center">
	 <td>8:30-9:30
	 <td>9:30-10:30
	 <td>10:3-11:30
	 <td>11:30-12:30
	 <td>12:30-2:00
	 <td>2:00-3:00
	 <td>3:00-4:00
	 <td>4:00-5:00
	</tr>
	<tr>
	 <td align="center">MONDAY
	 <td align="center">---<td align="center"><font color="blue">PYTHON<br>
	 <td align="center"><font color="pink">EDM<br>
	 <td align="center"><font color="red">WEB APPLICATION<br>
	 <td rowspan="6"align="center">L<br>U<br>N<br>C<br>H
	 <td align="center"><font color="maroon">MATHS<br>
	 <td align="center"><font color="brown">SOFT SKILLS<br>
	 <td align="center">counselling class
	</tr>
	<tr>
	 <td align="center">TUESDAY
	 <td align="center"><font color="blue">PYTHON<br>
	 <td align="center"><font color="red">EDM<br>
	 <td align="center"><font color="pink">WEB APPLICATION<br>
	 <td align="center">---
	 <td align="center"><font color="orange">MATHS<BR>
	 <td align="center"><font color="maroon">SOFT SKILLS<br>
	 <td align="center">library
	</tr>
	<tr>
	 <td align="center">WEDNESDAY
	 <td align="center"><font color="pink">PYTHON<br>
	 <td align="center"><font color="orange">EDM<BR>
	 <td align="center"><font color="brown">SWA<br>
	 <td align="center">---
	 <td colspan="3" align="center"><font color="green"> lab
	</tr>
	<tr>
	 <td align="center">THURSDAY
	 <td align="center">PYTHON<br>
	 <td align="center"><font color="brown">EDM<br>
	 <td align="center"><font color="orange">WEB APPLICATION<BR>
	 <td align="center">---
	 <td align="center"><font color="blue">MATHS<br>
	 <td align="center"><font color="red">SOFT SKILLS<br>
	 <td align="center">library
	</tr>
	<tr>
	 <td align="center">FRIDAY
	 <td align="center"><font color="orange">PYTHON<BR>
	 <td align="center"><font color="maroon"><br>
	 <td align="center"><font color="blue">WEB APPLICATION<br>
	 <td align="center">---
	 <td align="center"><font color="pink">MATHS<br>
	 <td align="center"><font color="brown">SOFTSKILLS<br>
	 <td align="center">library
	</tr>
	<tr>
	 <td align="center">SATURDAY
	 <td align="center"><font color="red">PYTHON<br>
	 <td colspan="3" align="center">seminar
	 <td align="center"><font color="pink">MATHS<br>
	 <td align="center"><font color="brown">SOFT SKILLS<br>
	 <td align="center">library
	</tr>

{% endblock %}

```


## OUTPUT
![image](https://github.com/Iswarya0580/slot/assets/149989171/f01e7655-41d3-447a-875c-782fe4e2a62b)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
