<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
/* Style page content */
body{
    background-image: linear-gradient(to bottom, #00f0f0, #eeffff);
    margin-left: 160px; /* Same as the width of the sidebar */
    padding: 0px 10px;
}
.genText {
    max-width: 700px;
    font-family: sans-serif; 
    color: #0;
}

.main {
  font-size: 110%; 
  line-height: 200%;
  max-width: 70%;
}

.pfp {
    float: right; 
    border-radius: 48%; 
    max-width: 430px; 
    height: auto;
}

.sidenav {
  height: 100%; /* Full-height: remove this if you want "auto" height */
  width: 150px; /* Set the width of the sidebar */
  position: fixed; /* Fixed Sidebar (stay in place on scroll) */
  z-index: 1; /* Stay on top */
  top: 0; /* Stay at the top */
  left: 0;
  background-color: #333; /* Black */
  overflow-x: hidden; /* Disable horizontal scroll */
  padding-top: 20px;
}

/* The navigation menu links */
.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  color: #333;
  display: block;
}

/* When you mouse over the navigation links, change their color */
.sidenav a:hover {
  color: #f1f1f1;
}

/* On smaller screens, where height is less than 450px, change the style of the sidebar (less padding and a smaller font size) */
@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
  .pfp {max-width: 100%;}
  .pfp {float: none;}
}
@media screen and (max-width: 1500px) {
  .main {max-width: 95%;}
  .genText {max-width: 95%;}
  .pfp {float: none;}
}
</style>
</head>

<div class="sidenav">
  <a href="#">About</a>
  <a href="#">Projects</a>
  <a href="#">Resume</a>
  <a href="#">Contact</a>
</div>

<header style="font-size: 170%;">
    <h1 style="border-style: solid; border-width: 5px; width: 289px"> Paul Bessler <h1>  
</header>

<div class="main">
    <img class="pfp" src="https://github.com/pwb574/Pauls_Portfolio/blob/main/Images/Paul_TIW.jpg?raw=true"/>
    
    <p class="genText">Hi, I'm Paul. I am currently pursuing my bachelors degree in Electrical and Computer Engineering at the University of Texas at Austin with a focus in Computer Architecture and Embedded Systems. Currently I am performing research on stochastic computing using Magnetic Tunnel Junctions at the Integrated Nano Computing (INC) Lab at UT.</p>
    <p class="genText">Some of my hobbies include rock climbing, watching movies, and 3D printing.</p>
    <h2 style="padding-top: 20px;">Welcome To My Portfolio</h2>
    <p class="genText">Feel free to look around and explore some of the many academic and personal projects that I have worked on. As a developing computer engineer, my goal is to explore as many aspects of this field as possible through professional, academic, and personal projects. My projects can be found under the "Projects" tab along with explanations and pictures of each project. Feel free to reach out using my information below!</p>
    
</div>

</html>
