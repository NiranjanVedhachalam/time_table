# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable </title>
</head>
<body>
   <img src="./WhatsApp Image 2024-10-10 at 14.06.38_11ab5b28.jpg" alt="">
    <table border="10">
      <div>
     <tr>
        <th bgcolor="yellow">time day</th>
        <th>8-10</th>
        <th>10-12</th>
        <th  bgcolor="yellow"rowspan="7"><p style="writing-mode: vertical-rl;">LUNCH</p></th>
        <th>1-3</th>
        <th>3-5</th>
     </tr>
   </div>
     <tr>
        <th bgcolor="yellow">Monday</th>
        <td >free slot </td>
        <td> web application</td>
        <td> principle of chemistry</td>
        <td>free slot </td>
     </tr>
     <tr>
        <th bgcolor="yellow"> Tuesday</th>
        <td>free slot </td>
        <td>free slot </td>
        <td>engineering model design</td>
        <td>free slot </td>
     </tr>
     <tr>
        <th bgcolor="yellow"> Wednesday</th>
        <td>Engineering model design</td>
        <td> python program</td>
        <td>free slot </td>
        <td>free slot </td>
     </tr>
     <tr>
        <th bgcolor="yellow">Thursday</th>
        <td >free slot </td>
        <td>principle of chemistry</td>
        <td>web application</td>
        <td> free slot</td>
     </tr>
     <tr>
        <th bgcolor="yellow">Friday</th>
        <td >free slot </td>
        <td> statistic</td>
        <td>python program</td>
        <td>free slot </td>
     </tr>
     <tr>
        <th bgcolor="yellow">Saturday</th>
        <td>free slot </td>
        <td>carrer development</td>
        <td>statistic</td>
        <td>web application</td>
        </tr>
    </table>
    <h2>Slot name </h2>
    <table border="1px solid black">
      <tr>
         <th>sno</th>
         <th>Code</th>
         <th>Subject</th>
      </tr>
      <tr>
         <td>1</td>
         <td>19301</td>
         <td>Web application</td>
      </tr>
      <tr>
         <td>2</td>
         <td>19422</td>
         <td>principle of chemistry</td>
      </tr>
      <tr>
         <td>3</td>
         <td>19404</td>
         <td>statistics </td>
      </tr>
      <tr>
         <td>4</td>
         <td>19201</td>
         <td>python program </td>
      </tr>
      <tr>
         <td>5</td>
         <td>19309</td>
         <td>Career development</td>
      </tr>

    </table>
    </body>
</html>       

```
# OUTPUT
![Screenshot 2024-12-05 140139](https://github.com/user-attachments/assets/12adf4f7-03d8-4219-b658-053fe83873e8)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
