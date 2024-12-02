# Ex03 Time Table
# Date:30/10/2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.
```
## STEP 3
Create a simple table using '<table>' tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>time table</title>
    <link rel="stylesheet" href="time table.css">
</head>
<style>
    .ta2{
        border-style: solid;
        border-collapse: collapse;
        border-width: 2px;
        width: 800px;

    }
    *{
    margin: 0%;
   
    text-decoration: none;
    border-width: 3px;
    border-collapse: collapse;
    margin-left: 5px;

    

}   
img{
    width: 100%;
}
table,th,td{
    
    border: 2px solid blue;
    height: 60%;
    text-align: center;
    padding:7px;
    text-decoration: none;
    border-radius: 2px;
    border-width: 2px;
    border-style: solid;
    border-collapse: collapse;
    text-decoration: none;
    
     color: aliceblue;
    background-color: black; 
}


.table:hover{
    cursor: pointer;
}
</style>
<body>
    <img src="sec logo.jpg" alt="logo">
    <br>
    <center>
    <table class="table" style="width: 85%; height: 35%;">
    <tr>
        <th>DAY/TIME</th>  
         
         <th>8-10</th>  
           <th>10-12</th> 
           <th rowspan="7" style="writing-mode:horizontal-tb; padding: 10px; text-align:justify; text-align: center;" > L <br> U <br> N <br> C <br>H</th>
          
            <th>1-3</th> 
            <th>3-5</th> 
    </tr><br>
    <tr>
        <th>MON</th>
        <td style="padding-left: 58px;" colspan="2"><abbr title="free time">---</abbr></td>
        
       
        <td style="color: blue"><abbr title="Introduction to web development">19AI414</abbr></td>
        <td  style="padding-left: 25px;"><abbr title="free time">---</abbr></td>
    </tr>
    <tr> 
        <th>TUE</th>
        <td style="color: rgb(231, 9, 9);"><abbr title="Career Development Skills">19EY708</abbr></td>
        <td style="color: rgb(237, 139, 11);"><abbr title="Statistics and Numerical Methods">19MA211</abbr></td>
        
        <td  style="padding-left: 25px;"><abbr title="free time">---</abbr></td>
        <td  style="padding-left: 25px;"><abbr title="free time">---</abbr></td>
       
        

    </tr>
    <tr>
        <th>WED</th>
        <td  style="padding-left: 25px;">---</td>
        <td style="color: rgb(84, 236, 20);"><abbr title="Introduction to C Programming">19AI304</abbr></td>
       
        <td style="padding-left:5px; color: rgb(223, 21, 196);"> <abbr title="MENTOR MEET">ECA-M</abbr></td>
        <td style="color:cyan;"><abbr title="Principles of Chemistry in Engineering">19CY205</abbr></td>
         
    </tr>
    <tr>
        <th>THURS</th>
        <td style="color: rgba(250, 204, 89, 0.923);" rowspan="2"><abbr title="Introuction to Machine Learning">19AI410</abbr></td>
        <td  style="padding-left: 25px;"><abbr title="free time">---</abbr></td>
       
        <td style="color: rgb(84, 236, 20);"><abbr title="Introduction to C Programming">19AI304</abbr></td>
        <td  style="padding-left: 25px;"><abbr title="free time">---</abbr></td>
    </tr>
    <tr>
        <th>FRI</th>
      
        <td style="color: rgb(9, 130, 235);" rowspan="2"><abbr title="Introduction to web development">19AI414</abbr></td>
       
        <td  style="padding-left: 25px;" ><abbr title="free time">---</abbr></td>
        <td  style="padding-left: 25px;"><abbr title="free time">---</abbr></td>

    </tr>
    <tr>
        <th>SAT</th>
        <td  style="color: rgb(237, 139, 11);"><abbr title="Statistics and Numerical Methods">19MA211</abbr></td>
       
        
              
       <td style="color:cyan;"><abbr title="Principles of Chemistry in Engineering">19CY205</abbr></td>
       <td  style="padding-left: 25px;"><abbr title="free time">---</abbr></td>
        </tr>
</table>
<br>
<br>

<table class="ta2">
    <tr>
       <th>S.NO</th>
       <th>SUB.CODE</th>
       <th>SUB.NAME</th>
    </tr>
    <tr>
        <td>1</td><br>
        <td>19AI414</td>
        <td>Introduction to web development</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19EY708</td>
        <td>career development skills</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19MA211</td>
        <td>Statistics and Numerical Methods</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19AI304</td>
        <td>Introduction to C Programming</td>
    </tr>
    <tr>
        <td>5</td>
        <td>ECA-M</td>
        <td>MENTOR MEET</td>
    </tr>
    <tr> 
        <td>6</td>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering</td>
    </tr>
    <tr>
        <td>7</td>
        <td>19AI410</td>
        <td>Introuction to Machine Learning</td>
    </tr>
</table>


<footer style="background-color: black; color: white; height: 25px;">
    &copy Designed by chan.All rights are reserved.
</footer>
</center>
</body>
</html>
```
# OUTPUT
![Screenshot 2024-12-02 143331](https://github.com/user-attachments/assets/03df31b2-cdab-481d-9685-b73270fda4b7)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
