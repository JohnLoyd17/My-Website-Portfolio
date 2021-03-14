# My-Website-Portfolio
This is my website portfolio,I created this using
HTML.

Comment:This code will be on your index.html
    👇
   
<!DOCTYPE html>
<html>

<head>
<title>Portfolio Website of John Loyd P. Mirasol  </title></head>
<link rel="stylesheet" type="text/css" href="style.css"> </link>
</head>

<body id="body">
 <h1 id = "Greetings"> Welcome to My Portfolio Website </h1>

 <div id ="MyInfo">
  <p><strong id ="name">John Loyd P. Mirasol </strong> <br><br>
  I am a Senior High student(Grade 12) <br> 
  from San Francisco <br>
  High School.
  I am<br> hardworking person.<br> 
  I will fulfill my
  goals<br> in life in time.<br> </p>
 </div>
 
  <div id="Image">
  <img src="Images/John Loyd.png" id="MyImage">  </img>
 </div><br>
 
<div id="Dreams"> 
 <h2 id ="dreamstext">Big Dream </h2>
 <strong>My dream is to become a professional programmer
    because <span class = "dreamcolor">I want to learn</span> coding a lot and
    <span class = "dreamcolor">I Love to Code</span> it's like
    <span id="soul"> it is my soul </span>to continue
    in my life.In specific I want to become a 
    HTML programmer or as knowed as a "website programmer".
    I always wanted to create a website that can help humans.
 </strong>
  
</div>
  
 
 
 
<div id = "Experience">  
 
 <p>
 <strong id = "experiences">Experience</strong><br>
 Java Basic Concepts of Console Programs<br>
 Basic HTML(Website Programmer)<br><br>

<em id="ExperienceQoute"> This are the current skills I have yet I can improve 
 it and add more skills to it because I hunger to learn
  more in the field of programming </em>
 </p>

<button class = "HireMeButton"> 
<a href="https://www.facebook.com/johnloyd.mirasol.3 "
id ="button"> 
 Hire Me </a></button>
</div><br><br><br>
 
<footer> 
 
<h6> Courtesy by:John Loyd P. Mirasol
 <span id ="myfb"><a href = "https://www.facebook.com/johnloyd.mirasol.3" 
 id = "FB">Facebook:John Loyd Mirasol</a> </span><br>

 <span id="myemail">
 <a href ="https://johnloydmirasol0@gmail.com"
 id ="email"> Email:johnloydmirasol0@gmail.com </a> </span> 
 
 <span id ="mygmail">
 <a href ="https://johnloydmirasol0@gmail.com" 
 id = "gmail"> 
  Gmail:johnloydmirasol0@gmail.com </a> </span>

</h6>  

</footer>
 
</body> 
</html>

---------------------------------------------------
Comment:This another code will be on your 
separate file.css
👇
#Greetings{
color:blue;
text-align:center;
line-height:50px;}



#body{
background-color:#00FFFF;
line-height:20px ; width:400px;
}

#name{color:navy;}
#button{text-decoration:none;}


#MyImage{width:170px ; height:200px;float:right ;
padding-right:20px;
}



#Image{float:right;padding:3px;padding-top:25px;}



#MyInfo{margin-left:3px;
color:blue;width:200px;float:left;padding-left:1px;}



#Dreams{
  color:navy;
  text-align:left;
  margin-top:250px; text-align:center;
  margin-right: 8px;
  }
 

#dreamstext{border:4px solid blue ;
 color:navy;
 margin-left:100px;
 margin-right:100px;
 background:lightblue;
 border-radius:10px;
 padding: 5px;
 padding-left:1px;
 padding-right:1px;
 text-align:center;}
 
 .dreamcolor{color:green;}
 
 #soul{color:black;}
  
#Experience{ 
margin-top:39px;
line-height:25px ;
color:green;
}




#experiences{
border-radius:5px;
color:navy ;
border:3px solid navy;
background-color:lime;
font-size:25px;}

#ExperienceQoute{color:navy;}

.HireMeButton{
padding:5px;
border:1px solid white ;
border-radius:100px;
background-color:;
}

#myfb{text-align:right; 
margin-left:90px;
color:blue;
}
#FB{text-decoration:none;}


#myemail{
color:indianred;
text-align:left;}

#email{
color:indianred ;
text-decoration:none ;}


#mygmail{text-align:right;
color:red;
background-color:white;
margin-left:40px;
}

#gmail{
text-decoration:none;
color:red;
}
