# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function fun()
{
    var mark1, mark2, mark3, mark4, mark5, total, percentage;
    mark1 = parseInt(prompt("Enter Subject-1 Marks"));
    mark2 = parseInt(prompt("Enter Subject 2 Marks"));
    mark3 = parseInt(prompt("Enter Subject 3 Marks"));
    mark4 = parseInt(prompt("Enter Subject 4 Marks"));
    mark5 = parseInt(prompt("Enter Subject 5 Marks"));
    total = mark1 + mark2 + mark3 + mark4 + mark5;
    percentage = total / 5;

    if (percentage >= 91 && percentage <= 100)
    {
        alert("O Grade");
    }
    else if (percentage >= 81 && percentage <= 90)
    {
        alert("A+ Grade");
    }
    else if (percentage >= 71 && percentage <= 80)
    {
        alert("A Grade");
    }
    else if (percentage >= 61 && percentage <= 70)
    {
        alert("B+ Grade");
    }
    else if (percentage >= 51 && percentage <= 60)
    {
        alert("B Grade"); 
    }
    else
    {
        alert("RA Grade");
    }
}
</script>
</head>
<body onload="fun()">
Check the result
</body>
</html>
```

## OUTPUT
![Screensho![Screenshot (7)](https://github.com/Premkumar171223/Ex06_Web-Design/assets/127816632/02c243ef-4372-4962-8ac6-23634a9a93ac)
t (6)](https://github.com/Premkumar171223/Ex06_Web-Design/assets/127816632/98b49694-ccac-429c-ad3c-5ba9f6b9ec27)
![Screenshot (8)](https://github.com/Premkumar171223/Ex06_Web-Design/assets/127816632/0836769d-3ed8-4a6c-a466-0259cdd68b5d)



## RESULT
  Student result using JavaScript is created successfully.
