# Ex03 Time Table
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
<html>
   <title> TIME TABLE </title>
   <body>
   <center>
   <img src="logo.png"height="100" width="540">
<table border="6" bgcolor="cyan" cellspacing="10" cellpadding="10">
<caption aria-busy="bold"> SLOT TIME TABLE - VAISHNAVIDEVI (212223040230) </caption>

<tr bgcolor="yellow">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th>
     <th> Saturday</th> 
</tr>
<tr align="center">
   <th bgcolor="yellow"> 8-10 </th>
   <td> DIGITAL</td>
   <td>FREE SLOT </td>
   <td> FREE SLOT</td>
   <td> WEB APPLICATION </td>
   <td> WEB APPLICATION </td>
   <td> PROBABILITY</td>
</tr>
<tr align="center">
    <th bgcolor="yellow"> 10-12 </th>
    <td>SOFTWARE </td>
    <td> PYTHON </td>
    <td> SOFTWARE</td>
    <td> PROBABILITY</td>
    <td> FREE SLOT</td>
    <td> OS</td>
</tr>
<tr align ="center">
    <th bgcolor="yellow"> 12-1 </th>
    <td colspan="6" align="center"> LUNCH </td>
</tr>
<tr align ="center">
    <th bgcolor="yellow"> 1-3 </th>
    <td>CS</td>
    <td> FREE SLOT </td>
    <td> PYTHON</td>
    <td> FREE SLOT</td>
    <td> FREE SLOT</td>
    <td> FREE SLOT</td>
</tr>
<tr align ="center">
    <th bgcolor="yellow"> 3-5 </th>
    <td> OS</td>
    <td> WEB APPLICATION</td>
    <td> FREE SLOT</td>
    <td> DIGITAL</td>
    <td> FREE SLOT</td>
    <td> FREE SLOT</td>
</tr>
</tr>
</table>
<br>
<table border="7" cellspacing="10" cellpadding="10">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td> 1. </td>
<td> 19AI414 </td>
<td> Fundamentals of Web Applicaton Development(WEB APPLICATION) </td>
</tr>
<tr align="center">
<td> 2. </td>
<td> 19MA222 </td>
<td> Probability and Queueing Model(PROBABILITY) </td>
</tr>
<tr align="center">
<td> 3. </td>
<td> 19EY702 </td>
<td> Creative skills (CS) </td>
</tr>
<tr align="center">
<td> 4. </td>
<td> 19EE404 </td>
<td> Digital Electronics(DIGITAL) </td>
</tr>
<tr align="center">
<td> 5. </td>
<td> 19CS408 </td>
<td> Software Engineering(SOFTWARE) </td>
</tr>
<tr align="center">
<td> 6. </td>
<td> 19CS405</td>
<td> Operating System(OS) </td>
</tr>
<tr align="center">
    <td> 7.</td>
    <td> 19AI301</td>
    <td> Python Programming(PYTHON)</td>
    </tr>
    
    </center>
    </body>
</html>
```

## OUTPUT
![slot](https://github.com/vaishnavidevi23013992/slot/assets/151864235/52974ab5-3d83-4102-b391-64beff3999c5)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
