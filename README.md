Home.html
-----------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title>Document</title>

<link rel="stylesheet" href="javajam.css">
</head>
<body>
    <div class="container-fluid wrapper">


    <div class="col-sm-3 sidenav">
      <img src="javajamlogo.jpg" class="img-responsive" alt="Java">
      <ul class="nav nav-pills nav-stacked" id="link">
        <b><li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="music.html">Music</a></li>
        <li><a href="jobs.html">Jobs</a></li></b>
      </ul><br>
    </div>


    <div class="col-sm-9 head">
      <h1><b>Javajam Coffee House</b></h1>

    </div>


    <div class="col-sm-9 wind">
      <img src="windingroad.jpg" class="img-responsive backdrop" alt="backdrop">
    </div>


    <div class="col-sm-9 text">
      <h2><b>Follow the Winding Road to JavaJam<b></h2>
      <p id="intro">We're a little out of the way, but take a drive down Route 42 to JavaJam today! Indulge in our locally roasted free-trade
         coffee and home made pastries. You' ll feel right at home at JavaJam!</p>
      <h3>JavaJam Coffee House features:</h3>
      <ul id="features">
        <li>Specialty Coffee and Tea</li>
        <li>Bagels, Muffins, and Organic Snacks</li>
        <li>Music and Poetry Readings</li>
        <li>Open Mic Night Every Friday</li>
      </ul>
      <div id="address">
        54321 Route 42<br>
        Ellison Bay, WI 54210<br>
        <a id="phone" href="#">888-555-5555</a>
      </div>
    </div>


      <footer class="container-fluid footer">
      <p>Copyright&#169 2017 JavaJam Coffee House</p>
   
</footer>


</div>

</body>
</html>
-----------------------------------------------------------------------------
javajam.css
--------------------------------------------------
*,
*:before,
*:after{
margin: 0px;
padding:0px;
box-sizing: border-box;
}
.wrapper{
height:662px;
width:100%;
font-style: verdana sans-serif;
overflow: hidden;
}
.sidenav{
background-color: #6E2C00;
height:90%;
width:10%;
text-align: center;
text-decoration: none;
display: inline-block;
border-bottom: 2px solid black;
}
img{
width:100px;
height:100px;
}
/*.nav-stacked{
margin-top: 10px;
color:white;
text-decoration: none;
}*/
a{
margin-top: 10px;
text-decoration: none;
color:#FCEBB6;

}


.head{
height:10%;
width:90%;
background-color:#D2B48C ;
float:right;
display: inline-block;
padding:5px 0px 0px 20px;
}
h1{
line-height: 200%
}


.wind{
height:30%;
width:90%;
float:right;
display:inline-block;
margin-top: -530px;/*doubt*/

}
.backdrop{

height:100%;
width:100%;
}


.text{
background-color: #FCEBB6;
width:90%;
height:50%;
float:right;
display:inline-block;
margin-top: -331px;
border-bottom: 2px solid black;
}
h2{
padding:15px 0px 0px 20px;
}
#intro{
padding:15px 0px 0px 30px;
}
h3{

padding:15px 0px 0px 15px;
}
#type1{
padding:5px 0px 0px 30px;
}
h4{
font-size: 20px;
padding:10px 0px 0px 15px;
}
#type2{
padding:5px 0px 0px 30px;
}
h5{
font-size: 20px;
padding:10px 0px 0px 15px;
}
#type3{
padding:5px 0px 0px 30px;
}
#features{
padding:15px 0px 0px 25px;
}
#address{
padding:15px 0px 0px 25px;
}

.footer{
background-color: #D2B48C;
height:10%;
width:100%;
text-align: center;
padding-top: 10px;
font-size: 0.60em;

}

#phone{
color:blue;
}
#name{
color:blue;
}

.jan{
background-color: #D2B48C;
height:30px;
margin:10px 0px 0px 0px;
padding: 0px 0px 10px 20px;
font-size: 25px;
border-bottom: 2px solid black;
}
.jan-content>img{
height:60px;
width:60px;
margin:15px 0px 0px 330px;
}
#jan-text{
margin:10px 0px 0px 15px;
}
.feb{
background-color: #D2B48C;
height:30px;
margin:10px 0px 0px 0px;
padding: 0px 0px 10px 20px;
font-size: 25px;
border-bottom: 2px solid black;
}
.feb-content>img{
    height:60px;
    width:60px;
    margin:15px 0px 0px 330px;
}
#feb-text{
    margin:10px 0px 30px 15px;
}


.jobs{
background-color: #FCEBB6;
width:90%;
height:80%;
float:right;
margin-top: -530px;
border-top: 30px solid #6E2C00;
border-bottom: 2px solid black
}

.name{

margin:60px 0px 0px 200px;
}

.email{
margin:40px 0px 0px 195px;
}

.exp{
margin:40px 0px 0px 165px;
}

.btn{
margin:100px 0px 0px 300px;
}
---------------------------------------------------------------------------
jobs.html
-------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title>Document</title>

<link rel="stylesheet" href="javajam.css">
</head>
<body>
    <div class="container-fluid wrapper">


    <div class="col-sm-3 sidenav">
      <img src="javajamlogo.jpg" class="img-responsive" alt="Java">
      <ul class="nav nav-pills nav-stacked" id="link">
      <b> <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="music.html">Music</a></li>
        <li><a href="jobs.html">Jobs</a></li></b>
      </ul><br>
    </div>


    <div class="col-sm-9 head">
      <h1><b>Javajam Coffee House</b></h1>

    </div>

    <div class="col-sm-9 jobs">


      <h2><b>Jobs at Javajam<b></h2>
      <p id="intro">Want to work at Javajam? Fill out the form below to start your application. Required fields are marked with an asterisk(*).</p>

      <form class="form-block">
<div class="form-group name">
    <label for="exampleInputName2 ">*Name:</label>
    <input type="text" class="form-control" id="exampleInputName2" placeholder="Your Name">
</div>
<div class="form-group email">
    <label for="exampleInputName2">*E-mail:</label>
    <input type="text" class="form-control" id="exampleInputName2" placeholder="Your Email">
</div></form>
<form class="form-horizontal">
<div class="form-group exp">
    <label for="exampleInputName2">*Experience:</label>
    <textarea class="form-control" rows="3" placeholder="description"></textarea></div>

</form>
<form>
<button type="submit" class="btn btn-default">Apply Now</button>
</form>


    </div>


      <footer class="container-fluid footer">
      <p>Copyright&#169 2017 JavaJam Coffee House</p>
  
</footer>


</div>

</body>
</html>
--------------------------------------------------------------------------------------------------
Menu.html
-------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title>Document</title>

<link rel="stylesheet" href="javajam.css">
</head>
<body>
    <div class="container-fluid wrapper">


    <div class="col-sm-3 sidenav">
      <img src="javajamlogo.jpg" class="img-responsive" alt="Java">
      <ul class="nav nav-pills nav-stacked" id="link">
      <b> <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="music.html">Music</a></li>
        <li><a href="jobs">Jobs</a></li></b>
      </ul><br>
    </div>


    <div class="col-sm-9 head">
      <h1><b>Javajam Coffee House</b></h1>

    </div>

    <div class="col-sm-9 wind">
      <img src="mugs.jpg" class="img-responsive backdrop" alt="backdrop">
    </div>


    <div class="col-sm-9 text">
      <h2><b>Coffee at Javajam<b></h2>
      <p id="intro">Indulge in our locally roasted free-trade and enjoy the aroma, the smooth taste, the caffine! Join our mug and
      get a 10% discount on each cup of coffe you purchase -- ask the barista for details.</p>
      <h3><b>Just Java</b></h3>
      <p id="type1">Regular house blend, decaffeinated coffee, or flavor of the day.<br>
      Endless Cup $2.00</p>
      <h4><b>Cafe au Lait</b></h4>
      <p id="type2">House blended coffee infused into a smooth, steamed milk.<br>
      Single $2.00 Double $3.00</p>
      <h5><b>Iced Cappuccino</b></h5>
      <p id="type3">Sweetened Espresso blended with icy-cold milk and served in a chilled glass<br>
      Single $4.75 Double $5.75</p>
    </div>


      <footer class="container-fluid footer">
      <p>Copyright&#169 2017 JavaJam Coffee House</p>
    
</footer>


</div>

</body>
</html>
--------------------------------------------------------------------------
Music.html
-------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title>Document</title>

<link rel="stylesheet" href="javajam.css">
</head>
<body>
    <div class="container-fluid wrapper">


    <div class="col-sm-3 sidenav">
      <img src="javajamlogo.jpg" class="img-responsive" alt="Java">
      <ul class="nav nav-pills nav-stacked" id="link">
      <b> <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="music.html">Music</a></li>
        <li><a href="jobs.html">Jobs</a></li></b>
      </ul><br>
    </div>


    <div class="col-sm-9 head">
      <h1><b>Javajam Coffee House</b></h1>

    </div>

    <div class="col-sm-9 wind">
      <img src="e-guitar-1736291_640.jpg" class="img-responsive backdrop" alt="backdrop">
    </div>


    <div class="col-sm-9 text">

          <h2>Music at JavaJam</h2>
          <p id="intro">The first friday night each month at JavaJam is a special night. Join us from 8pm to 11pm for some music you won't want
            to miss!</p>


        <div class="jan">
          <p><b>January</b></p>
        </div>
        <div class="jan-content">
          <img src="melaniethumb.jpg" alt="No Image found">
          <span id="jan-text">Melanie Morris ebtertains with her melodic folk style</span>
        </div>

        <div class="feb">
          <p><b>February</b></p>
        </div>
        <div class="feb-content">
          <img src="gregthumb.jpg" alt="No Image found">
          <span id="feb-text">Tahoe Greg is back from his tour. New songs. New stories</span>
    </div>
</div>


      <footer class="container-fluid footer">
      <p>Copyright&#169 2017 JavaJam Coffee House</p>
   
</footer>


</div>

</body>
</html>
