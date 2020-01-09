<html>
<head>
<title>Page Title</title>
<style>
body {
  background-color: black;
  text-align: left;
  link: teal;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
}
a{
    color: silver;
    font-family:新明細體;
    text-align: left;
}
</style>
<head>
<body>

<h1><font face="Arial" size="7">Andy Kuo</font></h1>
<hr>
<img src="1.jpg" alt="Avatar" style="width:500px" align="center">
<p><font color="teal" size="5"><b>NAME</b></font> : 郭珈源</p>
<p><font color="teal" size="5"><b>GENDER</b></font> : Boy</p>
<p><font color="teal" size="5"><b>CONSTELLATION</b></font> : Taurus</p>
<p><font color="teal" size="5"><b>GRADE</b></font> : 資工系23級</p>
<p><font color="teal" size="5"><b>INTEREST</b></font> : 
<ol>
       <li>游泳</li>
       <li>健身</li>
       <li>只要遠離原文書就好</li>
</ol> 
</p>
<p><font color="teal" size="5"><b>STUDY</b></font> : 
<ul>
  <li>新竹市清華大學</li>
  <li>桃園市陽明高中</li>
  <li>桃園市振聲國中</li>
  <li>桃園市北門國小</li>
</ul>
</p>
<p><font color="teal" size="5"><b>HOME</b></font> : Taoyuan</p>
<p><font color="teal" size="5"><b>EMAIL</b></font> : 17831783andy@gmail.com</p>
<p><font color="teal" size="5"><b>PHONE</b></font> : 0968-679-232</p>

<marquee scrollamount="100"><a href="https://kuo-chia-yuan.github.io/Personal_Blog/"><B><font color="gray" size="10"><b>surprise</b></font></a></marquee>


<script language="JavaScript">
function ShowTime(){
　document.getElementById('showbox').innerHTML = new Date();
　setTimeout('ShowTime()',1000);
}
</script>
<body onload="ShowTime()">
<div onclick="ChangeColor('white')" style="background-color: fuchsia; border:3px double; width:150px;height:70px;float:right;">
<div id="showbox"></div>
