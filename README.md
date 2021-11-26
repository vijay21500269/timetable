# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>
	
   <body>
      <table border = "8" cellspacing="3" bordercolor="yellow" bgcolor="skyblue">
      <ing src="logo.png">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         <tr>
<th colspan="2">Reference number:</th>
<th colspan="2" align="left">21500269</th>
<th colspan="2">Name:<th>
<th colspan="2" align="left">Vijay</th>
         <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
            <th>4</th>
<th>5</th>
<th>6</th>
<th>7</th>

         </tr>
        
<tr>
             <td>MONDAY</td>
             <td colspan="2">soft skills</td>
             <td colspan="2">linear algebra</td>
	     <td>Mentoring</td>
             <td colspan="2">maths for AI</td>
             
         </tr>
  
         
      
      
   


             <td>TUESDAY</td>
             <td colspan="2">web technology</td>
             <td colspan="2">engineering mechanics</td>
             <th rowspan="4">LUNCHBREAK</th>
             <td colspan="2">engineering design and modeling</td>
            
         </tr>
  
  	     <td>WEDNESDAY</td>
             <td colspan="2">Fundamentals of web technology</td>
             <td colspan="2">maths for AI</td>
             <td colspan="2">no class</td>
         </tr>
	     <td>THURSDAY</td>
             <td colspan="2">engineering design and modeling</td>
             <td colspan="2">python programming</td>
             <td colspan="2">engineering mechanics and product development</td>
             
         </tr>  
	     <td>FRIDAY</td>
             <td colspan="2">fundamentals of web technology</td>
             <td colspan="2">python programming</td>
             <td colspan="2">no class</td>
          </tr>  
	     <td>SATURDAY</td>
             <td colspan="7" align="center">LEAVE</td> 
 </tr>  
	     <td>SUNDAY</td>
             <td colspan="7" align = "center">LEAVE</td>           
      </table>
      
   </body>
</html>

~~~
# OUPUT
<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>
	
   <body>
<table border = "8" cellspacing="3" bordercolor="yellow" bgcolor="blue">
<img src="logo.png">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         <tr>
            <th colspan="2">Reference number:</th>
            <th colspan="2" align="left">21500269</th>
            <th colspan="2">Name:<th>
            <th colspan="2" align="left">Vijay</th>
         <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
            <th>4</th>
            <th>5</th>
            <th>6</th>
            <th>7</th>
          </tr>
          <tr>
             <td>MONDAY</td>
             <td colspan="2">19EY701-soft skills</td>
             <td colspan="2">19MA221-linear algebra</td>
	         <td>ECA051-ADMentoring</td>
             <td colspan="2">19MA220-maths for AI</td>
          </tr>
          <tr>
             <td>TUESDAY</td>
             <td colspan="2">19AI402-web technology</td>
             <td colspan="2">19AI303-engineering mechanics</td>
             <th rowspan="4">LUNCHBREAK</th>
             <td colspan="2">19AI302-engineering design and modeling</td>
         </tr>
         <tr>
  	     <td>WEDNESDAY</td>
             <td colspan="2">19AI401-Fundamentals of web technology</td>
             <td colspan="2">19MA220-maths for AI</td>
             <td colspan="2">no class</td>
         </tr>
         <tr>
	          <td>THURSDAY</td>
             <td colspan="2">19AI302-engineering design and modeling</td>
             <td colspan="2">19AI301-python programming</td>
             <td colspan="2">19AI303-engineering mechanics and product development</td>
         </tr> 
         <tr> 
	          <td>FRIDAY</td>
             <td colspan="2">19AI401-fundamentals of web technology</td>
             <td colspan="2">19AI301-python programming</td>
             <td colspan="2">no class</td>
         </tr> 
         <tr> 
	          <td>SATURDAY</td>
             <td colspan="7" align="center">LEAVE</td> 
         </tr> 
         <tr> 
	          <td>SUNDAY</td>
             <td colspan="7" align = "center">LEAVE</td>  
         </tr> 
      
   </body>
</html>