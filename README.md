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
<p><font color="teal" size="5">NAME</font> : 郭珈源</p>
<p><font color="teal" size="5">GENDER</font> : Boy</p>
<p><font color="teal" size="5">CONSTELLATION</font> : Taurus</p>
<p><font color="teal" size="5">GRADE</font> : 資工系23級</p>
<p><font color="teal" size="5">INTEREST</font> : 
<ol>
       <li>游泳</li>
       <li>健身</li>
       <li>只要遠離原文書就好</li>
</ol> 
</p>
<p><font color="teal" size="5">STUDY</font> : 
<ul>
  <li>新竹市清華大學</li>
  <li>桃園市陽明高中</li>
  <li>桃園市振聲國中</li>
  <li>桃園市北門國小</li>
</ul>
</p>
<p><font color="teal" size="5">HOME</font> : Taoyuan</p>
<p><font color="teal" size="5">EMAIL</font> : 17831783andy@gmail.com</p>
<p><font color="teal" size="5">PHONE</font> : 0968-679-232</p>
<marquee behavior="alternate"><a href="https://kuo-chia-yuan.github.io/Personal_Blog/"><B>surprise</b></a></marquee>

<script language="JavaScript">
function ShowTime(){
　document.getElementById('showbox').innerHTML = new Date();
　setTimeout('ShowTime()',1000);
}
</script>
<body onload="ShowTime()">
<div onclick="ChangeColor('white')" style="background-color: fuchsia; border:3px double; width:150px;height:70px;float:right;">
<div id="showbox"></div>
