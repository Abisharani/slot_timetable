# Ex03 Time Table
## Date:13.04.2025

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
<html>
    <center>
        <img src="logo.png.jpeg">
    </center>
    <head>
        <title>
            TIMETABLE
        </title>
        <style>
            table,th,td{
                text-align:center;
                border:3px solid rgb(9,9,9);
            }
        </style>

    </head>
    <body>
          <center>
            <h2 style="text-align:center,">TIMETABLE-Abisha Rani S 24900748</h2>
            <table>
                <tr>
                    <th bgcolor="purple">Day</th>
                    <th bgcolor="purple">8-10</th>
                    <th bgcolor="purple">10-12</th>
                   <th rowspan=7>l<br>u<br>n<br>c<br>h<br></th>
                    <th bgcolor="purple">1-3</th>
                    <th bgcolor="purple">3-5</th>
                    </tr>
                    <tr>
                        <td bgcolor="purple">Monday</td>
                        <td bgcolor="yellow"></td>
                        <td bgcolor="yellow">19CS408</td>
                        <td bgcolor="yellow">19AI305</td>
                        <td bgcolor="yellow"></td>
                    </tr>
                    <tr>
                        <td bgcolor="purple">Tuesday</td>
                        <td bgcolor="yellow"></td>
                        <td bgcolor="yellow">19PH814</td>
                        <td bgcolor="yellow">19MA222</td>
                        <td bgcolor="yellow">19EE305</td>
                    </tr>
                    <tr>
                        <td bgcolor="purple">Wednesday</td>
                        <td bgcolor="yellow"></td>
                        <td bgcolor="yellow">19AI414</td>
                        <td bgcolor="yellow">ECA-M</td>
                        <td bgcolor="yellow">19CS405</td>
                    </tr>
                    <tr>
                        <td bgcolor="purple">Thursday</td>
                        <td bgcolor="yellow"></td>
                        <td bgcolor="yellow">19AI303</td>
                        <td bgcolor="yellow">19PH814</td>
                        <td bgcolor="yellow">19EE305</td>
                    </tr>
                    <tr>
                        <td bgcolor="purple">Friday</td>
                        <td bgcolor="yellow"></td>
                        <td bgcolor="yellow">19AI303</td>
                        <td bgcolor="yellow">19MA222</td>
                        <td bgcolor="yellow">19AI414</td>
                    </tr>
                    <tr>
                        <td bgcolor="purple">Saturday</td>
                        <td bgcolor="yellow"></td>
                        <td bgcolor="yellow">19CS408</td>
                        <td bgcolor="yellow">19AI305</td>
                        <td bgcolor="yellow">19CS405</td>
                    </tr>
                   
            </table>

          </center>
    </body>
</html>
<br>
<br>
<center>
    <table>
        <tr>
            <th bgcolor="red">S.NO</th>
            <th bgcolor="red">Subject code</th>
            <th bgcolor="red">Subject name</th>
        </tr>
        <tr>
        <th bgcolor="red">1</th>
        <th bgcolor="sky blue">19CS408</th>
        <th bgcolor="sky blue">Software Engineering</th>
</tr>
<tr>
    <th bgcolor="red">2</th>
    <th bgcolor="sky blue">19AI305</th>
    <th bgcolor="sky blue">Advanced C Programing</th>
</tr>
<tr>
    <th bgcolor="red">3</th>
    <th bgcolor="sky blue">19PH814</th>
    <th bgcolor="sky blue">Physics for Quantum Computing</th>
   
</tr>
<tr>
    <th bgcolor="red">4</th>
    <th bgcolor="sky blue">19MA222</th>
    <th bgcolor="sky blue">probability and Queueing Models</th>
</tr>
<tr>
    <th bgcolor="red">5</th>
    <th bgcolor="sky blue">19EE305</th>
    <th bgcolor="sky blue">Basic Electrical,Electronics and Measurement Engineering</th>
</tr>
<tr>
    <th bgcolor="red">6</th>
    <th bgcolor="sky blue">19AI414</th>
    <th bgcolor="sky blue">Fundamentals of Web Application Development</th>
</tr>
<tr>
    <th bgcolor="red">7</th>
    <th bgcolor="sky blue">ECA-M</th>
    <th bgcolor="sky blue">Mentor Meet</th>
</tr>
<tr>
    <th bgcolor="red">8</th>
    <th bgcolor="sky blue">19CS405</th>
    <th bgcolor="sky blue">Operating System</th>
</tr>
<tr>
    <th bgcolor="red">9</th>
    <th bgcolor="sky blue">19AI303</th>
    <th bgcolor="sky blue">engineering Mechanics and Product Development</th>
</tr>
    </table>
</center>
```


## OUTPUT

![alt text](<Screenshot (7).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
