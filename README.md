# Ex03 Time Table
## Date:22.04.2025

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
<head>
<title>SEC time table</title> 
</head>
<body>
    

<!-- HTML TABLES -->

<table border="5"width="1000"height="600">
<tr>
    <th bgcolor="red">day/time</th>
    <th bgcolor="red">monday</th>
    <th bgcolor="red">tuesday</th>
    <th bgcolor="red">wednesdsay</th>
    <th bgcolor="red">thursday</th>
    <th bgcolor="red">friday</th>
    <th bgcolor="red">saturday</th>

    </tr>
<tr>
    <td bgcolor="red">8-10am</td>
    <td bgcolor="red">free slot</td>
    <td bgcolor="red">chemistry</td>
    <td bgcolor="red">python</td>
    <td bgcolor="red">free slot</td>
    <td bgcolor="red">free slot</td>
    <td bgcolor="red">free slot</td>

</tr>
<tr>
    <td bgcolor="red">10-12pm</td>
    <td bgcolor="red">web development</td>
    <td bgcolor="red">data science</td>
    <td bgcolor="red">web development</td>
    <td bgcolor="red">python</td>
    <td bgcolor="red">free slot</td>
    <td bgcolor="red">python</td>




</tr>
<tr>
    <td bgcolor="red">1-3pm</td>
    <td bgcolor="red">carrer development skills</td>
    <td bgcolor="red">python</td>
    <td bgcolor="red">mentor meeting</td>
    <td bgcolor="red">chemistry</td>
    <td bgcolor="red">data science</td>
    <td bgcolor="red">web development</td>

</tr>

 </table>

</body>
</html>
            <br>
            <table border="3" width="600">
                <tr>
                    <td>S.no</td>
                    <td>Subject code</td>
                    <td>Subject name</td>
                </tr>
                <tr>
                    <td>01</td>
                    <td>19AI403</td>
                    <td>Data science</td>
                </tr>
                <tr>
                    <td>02</td>
                    <td>19AI414</td>
                    <td>Web development</td>
                </tr>
                <tr>
                    <td>03</td>
                    <td>19MA220</td>
                    <td>maths for ai</td>
                </tr>
                <tr>
                    <td>04</td>
                    <td>19CY205</td>
                    <td>chemistry</td>
                </tr>
                <tr>
                    <td>05</td>
                    <td>19EY708</td>
                    <td>Career developmemt</td>
                </tr>
                <tr>
                    <td>06</td>
                    <td>19MA222</td>
                    <td>mentor meeting</td>
                </tr>
                
            </table>
        </body>
    
</html>
```


## OUTPUT
![image](https://github.com/user-attachments/assets/9d598a23-463c-4dd9-89aa-6e597949ada3)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
