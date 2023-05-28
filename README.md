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
~~~
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
    alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
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
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
~~~
## OUTPUT
![EX05 01](https://github.com/kaviyaelumalai/Ex06_Web-Design/assets/127817032/0ff41448-dc84-4bd1-9fc0-733f4cf122c3)
![EX05 02](https://github.com/kaviyaelumalai/Ex06_Web-Design/assets/127817032/c9509d41-a59f-4772-aa1a-f15a2cfbbb24)
![EX05 03](https://github.com/kaviyaelumalai/Ex06_Web-Design/assets/127817032/0078ad4a-6952-4417-9966-ceafa976d6cf)
![EX05 04](https://github.com/kaviyaelumalai/Ex06_Web-Design/assets/127817032/3dad9b03-244e-48ad-a08a-57147c8912e8)
![EX05 05](https://github.com/kaviyaelumalai/Ex06_Web-Design/assets/127817032/6f17fef9-19d6-49cb-addf-76e420595fda)
![EX05 06](https://github.com/kaviyaelumalai/Ex06_Web-Design/assets/127817032/3d1122a8-353b-42cd-a6ad-3e5cc2f64007)
![EX05 07](https://github.com/kaviyaelumalai/Ex06_Web-Design/assets/127817032/fc7306cc-5904-4646-bb72-e275a787557b)


## RESULT
  Student result using JavaScript is created successfully.
