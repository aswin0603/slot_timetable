# Ex03 Time Table

## Date: 06-02-2026

## AIM

To write a html webpage page to display your slot timetable.

## ALGORITHM

### STEP 1

Create a Django-admin Interface.

### STEP 2

Create a static folder and inert HTML code.

### STEP 3

Create a simple table using `<table>` tag in html.

### STEP 4

Add header row using `<th>` tag.

### STEP 5

Add your timetable using `<td>` tag.

### STEP 6

Execute the program using runserver command.

## PROGRAM

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>TimeTable</title>
  </head>
  <body>
    <section class="logo">
      <img src="logo.png" alt="Saveetha Logo" />
    </section>
    <hr size="2rem" />
    <section class="tables">
      <h2>Slot Time Table - ASWIN B (24900642)</h2>
      <table class="timetable">
        <tr>
          <th>Day/Time</th>
          <th>Monday</th>
          <th>Tuesday</th>
          <th>Wednesday</th>
          <th>Thursday</th>
          <th>Friday</th>
          <th>Saturday</th>
        </tr>
        <tr>
          <td>08:00 - 10:00</td>
          <td colspan="2">FWAD</td>
          <td>ADV. C</td>
          <td colspan="2">FREE SLOT</td>
          <td>ADV. C</td>
        </tr>
        <tr>
          <td>10:00 - 12:00</td>
          <td>FREE SLOT</td>
          <td>ADV. C</td>
          <td>FWAD</td>
          <td>ADV. C</td>
          <td>FWAD</td>
          <td>FREE SLOT</td>
        </tr>
        <tr>
          <td>12:00 - 01:00</td>
          <td colspan="6">LUNCH</td>
        </tr>
        <tr>
          <td>01:00 - 03:00</td>
          <td>DBMS</td>
          <td>FREE</td>
          <td>MENTOR MEET</td>
          <td>FWAD</td>
          <td>ADV. C</td>
          <td>FREE SLOT</td>
        </tr>
        <tr>
          <td>03:00 - 05:00</td>
          <td colspan="2">FREE SLOT</td>
          <td>DBMS</td>
          <td colspan="3">FREE SLOT</td>
        </tr>
      </table>

      <table class="details">
        <tr>
          <th>S. No.</th>
          <th>Subject Code</th>
          <th>Subject Name</th>
        </tr>
        <tr>
          <td>1.</td>
          <td>19AI414</td>
          <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
          <td>2.</td>
          <td>19AI305</td>
          <td>Advanced C Programming (ADV. C)</td>
        </tr>
        <tr>
          <td>3.</td>
          <td>19CS404</td>
          <td>Database Management Systems & it's Applications (DBMS)</td>
        </tr>
      </table>
    </section>
  </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2026-02-06 113937.png>)

## RESULT

The program for creating slot timetable using basic HTML tags is executed successfully.


Name : ASWIN B \
Register Number : 212224110007
