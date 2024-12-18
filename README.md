# Ex03 Time Table
## Date:15-11-2024

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
<HTML>
    <HEAD>
        <TITLE>Time Table</TITLE>
    </HEAD>
    <BODY>
        <img src="logo.png" width="500" height="100" >
        <TABLE border = "1"  cellpadding = "5" bgcolor = "#f4f6f7">
            <CAPTION>SLOT TIME TABLE - Akshay M (24900489)</CAPTION>
            <TR bgcolor = "#ec7063">
                <TH>DAY/TIME</TH>
                <TH>8 - 10</TH>
                <TH>10 - 12</TH>
                <TH rowspan = "7">Lunch</TH>
                <TH>1 - 3</TH>
                <TH>3 - 5</TH>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Monday</TH>
                <TD>Math</TD>
                <TD>English</TD>
                <TD colspan = "2">Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Tuesday</TH>
                <TD>Web Dev</TD>
                <TD>Digital Electronics</TD>
                <TD>EDM</TD>
                <TD>IOT</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Wednesday</TH>
                <TD>EDM</TD>
                <TD>English</TD>
                <TD>Mentor Meet</TD>
                <TD>Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Thursday</TH>
                <TD>Englsih</TD>
                <TD>Digital Electronics</TD>
                <TD colspan="2">Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Friday</TH>
                <TD colspan="2">Free Slot</TD>
                <TD>Web Dev</TD>
                <TD rowspan="2">Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Saturday</TH>
                <TD>Free Slot</TD>
                <TD>IOT</TD>
                <TD>Web Dev</TD>
            </TR>
        </TABLE>
        <BR>
        <TABLE border = "1"  cellpadding = "5">
            <CAPTION>Courses</CAPTION>
            <TR>
                <TH bgcolor = "#ec7063">S.No</TH>
                <TH bgcolor = "#ec7063">Course Code</TH>
                <TH bgcolor = "#ec7063">Course Name</TH>
            </TR>
                <TD>1.</TD>
                <TD>19AI414</TD>
                <TD>Fundamentals of Web Application Development</TD>
            </TR>
            <TR>
                <TD>2.</TD>
                <TD>19CS420</TD>
                <TD>Prototyping of IoT Systems</TD>
            </TR>
            <TR>
                <TD>3.</TD>
                <TD>19MA222</TD>
                <TD>Probability and Queueing Models</TD>
            </TR>
            <TR>
                <TD>4.</TD>
                <TD>19EN101 </TD>
                <TD>Communicative English</TD>
            </TR>
            <TR>
                <TD>5.</TD>
                <TD>19EE404</TD>
                <TD>Digital Electronics</TD>
            </TR>
            <TR>
                <TD>6.</TD>
                <TD>19AI302</TD>
                <TD>Engineering Design and Modelling</TD>
            </TR>
        </TABLE>
    </BODY>
</HTML>

```

## OUTPUT

![alt text](<Screenshot (35).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
