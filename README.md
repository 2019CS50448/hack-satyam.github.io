# hack-satyam.github.io
<!DOCTYPE html>
<html>
<head>
  <title>webpage</title>
  <style>
    body{
        background:url("ball.jpg") no-repeat;
        background-size:cover;
        color:white;
    }
    .header{
        background-color: black;
        color:blue;
        text-align: center;
        font-size: 40px;
    }
    h1{
        color:red;
    }
    ul {
        margin: 0px;
        padding: 0px;
        list-style:circle;
    }
    ul li {
        float: left;
        width: 200px;
        height: 40px;
        background-color: black;
        opacity:0.8;
        line-height:40px;
        text-align: center;
        font-size:20px;
        font-family: bell mt;
        position:sticky;
    }
    ul li a {
        text-decoration: none;
        color:white;
        display:block;
    }
    ul li a:hover {
        background-color:green;
        padding:5px;
    }
    ul li ul li{
        display:none;
    }
    ul li:hover ul li{
        display:block;
    }
    ul li ul li a:hover{
        background-color:red;
        padding:0px
    }
    .intro{
        text-align: center;
        font-size:20px;
    }
  </style>
</head>
<body>
  <div class = "header">Welcome to my portfolio</div>
  <h1><big><i>The Portfolio</i></big></h1>
  <p>
  <ul>
    <li><a>HOME</a></li>
    <li><a>ABOUT ME</a></li>
    <li><a>HOBBIES</a>
        <ul>
            <li><a>coding</a></li>
            <li><a>trekking</a></li>
            <li><a>maths</a></li>
            <li><a>hangouts</a></li>
        </ul>
    </li>
    <li><a>FUTURE GOALS</a>
        <ul>
            <li><a>Computer scientist</a></li>
            <li><a>Working at Google</a></li>
        </ul>
    </li>
    <li><a>CONTACT ME</a>
        <ul>
            <li><a href="https://www.facebook.com/satyam.modi.7731">facebook</a></li>
            <li><a href="https://mail.google.com/mail/u/0/#inbox">gmail</a></li>
        </ul>
    </li>
  </ul>
  <br/>
  </p>
  <hr>
  <div class = "mypic"><img src="satyam1.jpg"/></div>
  <div class = "intro">Hi everyone,I am Satyam Kumar Modi,a Btech student at <br/>IIT Delhi,Computer science and engineering<br/>
       I love algorithm designing and focus on mathematical<br/> aspect of computing.For more information ,surf to my portfolio.</div>

</body>
</html>
