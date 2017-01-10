<head>
  <!--Import Google Icon Font-->
  <link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <!--Import materialize.css-->
  <link type="text/css" rel="stylesheet" href="css/materialize.min.css" media="screen,projection" />

  <!--Let browser know website is optimized for mobile-->
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>

<body>
  <!--Import jQuery before materialize.js-->
  <script type="text/javascript" src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
  <script type="text/javascript" src="js/materialize.min.js"></script>
</body>

</html>
<!-- Compiled and minified CSS -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.8/css/materialize.min.css">

<!-- Compiled and minified JavaScript -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.8/js/materialize.min.js"></script>
<link href="https://fonts.googleapis.com/css?family=Bungee+Shade" rel="stylesheet">


<!--Do not change code above this line -->
<nav>
    <div class="nav-wrapper">
      <a href="https://github.com/anjneyM" class="brand-logo"> Anjney Mital
      </a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="#Info">Information</a></li>
        <li><a href="#Website2">Website 2</a></li>
        <li><a href="#Website1">Website 1</a></li>
        <li><a href="#End">Bottom</a></li>
        <li><a href="#Header">Top</a>
        </li>
        <li><a href="#Form">Contact Me</a></li>
        
      </ul>
    </div>
  </nav>
  <style>
  body{background-color:#1de9b6;}
.content{
  background-color:#eceff;
  box-shadow: 5px 5px 5px 5px ;
  margin: 20px;

}

h2 {font-family: 'Bungee Shade',cursive;
padding: 20px;

}
.sinfo {
  font-size: 40px;
  margin: 20px;
  padding: 20px;
}
.form{
  margin: 20px;
  padding: 20px;
}
.brand-logo{
  padding: 10px;
}
  
  
  
  
  
  </style>

<div id="Header" class=" content well container">
  <h2 class="heading"><font color="#1de9b6">Anjney Mital</font></h2>
  <div id="Info" class=" sinfo card hoverable">
    <p class="flow-text">
      I am a 14 year old Web Designer.
      <br> I can code in Python(2),Android,Arduino,HTML,CSS,jquery,Bash(Linux Terminal)<br> and also am well versed in computer hardware.
      <ul>Points About Me
        <li>Foodie</li>
          <li>Fueled By Coffee<li>
        <li>Gamer</li>
           <li>Friendly Guy</li>
             <li>Programmer</li>
        <li>Aspiring Entrepreneur</li>
    </ul>
    </p>
  </div>

  <div id="Website1" class="row">
    <div class="col s12 m7">
      <div class="card">
        <div class="card-image">
          <img src="http://i.imgur.com/bRDUmZL.png">
          <span class="card-title">Website #1</span>
        </div>
        <div class="card-content">
          <p>This is my tribute page for Dr.Abdul Kalam. Made on Codepen.io for a FreeCodeCamp challenge. It was made in 4 hours.</p>
        </div>
        <div class="card-action">
          <a href="https://codepen.io/anjneym/pen/egpgxo/">Go to his work</a>
        </div>
      </div>
    </div>
  </div>




<div id="Website2" class="row">
    <div class="col s12 m7">
      <div class="card">
        <div class="card-image">
          <img src="https://s30.postimg.org/xutk19fw1/git.png">
          <span class="card-title">Website #2</span>
        </div>
        <div class="card-content">
          <p>This is a WebPage that I use to test my skills and also to test different features.It is hosted on GitHub pages.</p>
        </div>
        <div class="card-action">
          <a href="https://anjneym.github.io/hello-world/">Go to his work</a>
        </div>
      </div>
    </div>
  </div>
<div class="card hoverable form" id="Form">
  If you want to contact me fill this form out.
  <form action="mailto:manjney@gmail.com" method="post" enctype="text/plain">
    Name:<br>
<input type="text" name="name">
E-mail:<br>
<input type="text" name="mail" required>
What do you want to say to me?:
<input type="text" name="comment" size="50" required>
    <br><br>
<input type="submit" value="Send"class="btn btn-default">
<input type="reset" value="Reset" class="btn btn-default">
  </form></div>
   </div>
   <script>
   $("h2").addClass("text-center")
   </script>






<footer class="page-footer">
  <div id="End" class="container">
    <div class="row">
      <div class="col l6 s12">
        <h5 class="white-text">Anjney
          mital
        </h5>
        <p class="grey-text text-lighten-4">Hope you like the WebSite!
          If you did,
          <br>
          Let me know</p>
      </div>
      <div class="col l4 offset-l2 s12">
        <h5 class="white-text">Links</h5>
        <ul>
          <li><a class="grey-text text-lighten-3" href="https://www.facebook.com/valordAnjney">Facebook</a></li>
          <li><a class="grey-text text-lighten-3" href="https://www.reddit.com/u/droidBoy5">Reddit </a></li>
          <li><a class="grey-text text-lighten-3" href="https://github.com/anjneyM/">GitHub</a></li>
          <li><a class="grey-text text-lighten-3" href="https://twitter.com/anjneymital
">Twitter</a></li>
        </ul>
      </div>
    </div>
  </div>
  <div class="footer-copyright">
    <div class="container">
      Made with love by Anjney Mital
      <a class="grey-text text-lighten-4 right" href="#!"> 2017</a>
    </div>
  </div>
</footer>
