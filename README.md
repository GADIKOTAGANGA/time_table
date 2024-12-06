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
````<!DOCTYPE html>
<html lang="en"
<head>
    <title>SLOT TIME TABLE</title>
</head>
<body>
        <center>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRKZfSj21lL4B0AeATFHKdFuH5NiLSknduUDg&s"
            height="100"
            width="540"
        </centre>
        <br>
        <table align="center"
        width="540"
        cellspacing="2"
        cellpadding="4"
        border="5"
        bgcolor="cyan">
        <caption><b>SLOT TIME TABLE-GangaDevi (24002379) </b></caption>
        <tr align="center">
        <th bgcolor="yellow">DAY/TIME</th>
        <th bgcolor="yellow">monday</th>
        <th bgcolor="yellow">tuesday</th>
        <th bgcolor="yellow">wednesday</th>
        <th bgcolor="yellow">thursday</th>
        <th bgcolor="yellow">friday</th>
        
    </tr>
    <tr align="center">
      <th bgcolor="yellow">8-10</th>  
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
      <td>PHY</td>
      <td>CHE</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td>GER</td>
        <td>FREE SLOT</td>
        <td>FWAD</td>
        <td>FWAD</td>
        <td>PHY</td>
    </tr>
    <tr>
        <th bgcolor="yellow">12-1</th>
        <td colspan="5" align="center">L U N C H B R E A K</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>MAT</td>
        <td>MAT</td>
        <td>SS</td>
    </tr> 
    <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>GER</td>
        <td>CHE</td>
        <td>FWAD</td>
    </tr>
    </table>
    <br>
    <table align="center"
    cellspacing="2"
    cellpadding="4"d
    border="2">
    <tr align="center">
    <th>SL.NO.</th>
    <th>subject code</th>
    <th>subject name</th>
    </tr>
    <tr>
        <td align="centre">1.</td>
        <td aligan="centre">19A1414</td>
        <td>Fundamental Of Web Application
         (FWAD)</td>
         </tr>
         <tr>
            <td align="centre">3.</td>
            <td align="centre">19PH206</td>
            <td>German Basic (GER)</td>
        </tr>
        <tr>
            <td align="centre">3.</td>
            <td align="centre">19PH206</td>
            <td>Physics For Information Technology</td>
         </td>
         </tr>
         <tr>
            <td align="centre">4.</td>
            <td align="centre">19CY205</td>
            <td>Principles Of Chemistry In
                Engineering(CHE)</td>
             </tr>
             <tr>
                <td align="centre">5.</td>
                <td align="centre">19MA201</td>
                <td>Calculus And Matrix Algebra (MAT) </td>
              </tr>
              <tr>
                <td align="centre">6.</td>
                <td align="centre">19EY701</td>
                <td>soft skills(ss)</td>
              </tr>
              </table>
            </body>
            </html>

          ````



# OUTPUT

![WhatsApp Image 2024-12-06 at 15 46 18_206f6dbb](https://github.com/user-attachments/assets/53b97398-cde5-429f-b109-6355b9a83929)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
