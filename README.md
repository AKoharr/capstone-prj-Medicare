# capstone-prj-Medicare
# Developer Details:
Name: Annu Rani Kohar
Email: annukohar@gmail.com 
Date created: 14-05-2023
Project: Medicare 
GitHub Repository:
https://github.com/AKoharr/capstone-prj-Medicare
Program Background:
Medicare is a company that supplies medicines and a couple of other healthcare essentials at an affordable price. It was established in 2012 in Delhi, India. It had been serving fine all these years; however, the business analysts noticed a decline in sales since 2017. They found out that online ordering of medicines with companies, such as 100mg and mfine are gaining more profits by eliminating middlemen from the equation. As a result, the team decided to hire a Full Stack developer to develop a healthcare web application with a rich and user-friendly interface.
You are hired as the Full Stack Java developer and are asked to develop the web application. The management team has provided you with the requirements and their business model so that you can easily arrange different components of the application.
Program Features:
●	Presenting the specification document which has the product’s
capabilities, appearance, and user interactions
 
●	Setting up Git and GitHub account to store and track your
enhancements of the prototype
●	Explaining the Java concepts used in the project
●	Discussing the generic features of the product:
●	There will be an admin to manage the website. An administrator login will be required to access the admin page.


The admin will be able to change his password if he wants, he should be able to:
●	Manage the products in the store including categorizing them
●	Browse the list of users who have signed up and be able to search users
●	See purchase reports filtered by date and category

Tools used for development:
1.	Eclipse IDE
2.	MySQL Relation Database Management System
3.	Apache Tom-Cat 10 server
4.	Spring Boot
5.	Spring MVC
6.	Java Servlets
7.	Java Server Pages (JSP)
8.	HTML
9.	Apache Maven
10.	JDBC Java Database Connectivity
11.	CSS
 



 

1.signup
 
Source codes
 



<!DOCTYPE  html>
<html>
<head>
<link  rel="stylesheet"  href="css/signup-style.css">
<title>Sign  up</title>
</head>
<body>
<div  id='container'>
<div  class='signup'>
<form  action="signupAction.jsp"  method="post">
<input  type="text"  name="name"  placeholder="Full  name">  <input type="email"  name="email"  placeholder="Email  ID">  <input type="number"  name="phonenumber"  placeholder="Mobile  Number">
<select  name="securityQuestion"  required>
<option  value="What  is  the  name  of  your  first  pet  ?">What is  the  name  of  your  first  pet  ?</option>
<option  value="What  is  your  first  car  ?">What  is  your first car ?</option>
<option  value="Where  did  you  born  ?">Where  did  you  born
 
?</option>



<input
 

<option  value="What  is  the  name  of  your  first  school  ?">What is  the  name  of  your  first  school  ?</option>
</select>  <input  type="text"  name="answer"  placeholder="Answer"> type="password"  name="password"  placeholder="Password">  <input
  

</form>
<h2>
 
type="submit"  value="Sign  Up">
 


</div>
 

</h2>
 
<a  href="login.jsp">Login</a>
 
<div  class='whysign'>
<%
String  msg  =  request.getParameter("msg");
if  ("valid".equals(msg))  {
%>
<h1>Successfully  Registered</h1>
<%
}
if  ("invalid".equals(msg))  {
%>

<h1>Some  thing  Went  Wrong!  Try  Again  !</h1>
<%
}
%>
</div>
</div>

</body>
</html>

