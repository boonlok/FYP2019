
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp" crossorigin="anonymous">

<style>

    .big-container
    {
    	background-color: #f7f2f2;
    }

/*	.navbar navbar-expand-lg navbar-light bg-light
	{
		background-color: #f7f2f2;
		font-family: 'Cairo', sans-serif;
		font-size: 20px;
		color: black;
	}*/

	@media only screen and (max-width: 1633px) {
    .logo
    {width: 100%}
    }

	.nav-item
	{
		margin-right: em;
	}
	
	.nav-link:hover 
	{
		
	}

	.middle-1
	{
         background-color: #f7f2f2;
	}

	.col-md-4
	{
		display: inline-block;
		float: left;
		text-align: center;
	}

	.btn-number
	{
		width:10%;
		border:none;
		padding:5px;
		border-radius: 10px;
		background-color:#ff5416;
		border-radius: 80%;
	}

	.btn-number:hover
	{
		background-color: #f49950;
	}

	p
	{ 
		font-size: 1.5em;
		font-family: 'Cairo', sans-serif;
		color: black;
	}
	
</style>

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>StallOwner Homepage</title>
  </head>
  <body>
    <div class="big-container">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#" style="width: 10%;">
  	<div class="logo-image" style="width: 100%;">
  		<img src="images/justrentlogo2.png" class="logo" style="width: 100%; height: 8%; margin-left: 1em;">
  	</div>
  </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href="StallOwner_Homepage.html" style="margin-left: 5em;font-size: 18px;
		font-family: 'Cairo', sans-serif;">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"style="margin-left:em;font-size: 18px;
		font-family: 'Cairo', sans-serif;">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"style="margin-left: em;font-size: 18px;
		font-family: 'Cairo', sans-serif;">Event</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"style="margin-left: em;font-size: 18px;
		font-family: 'Cairo', sans-serif;">Feedback</a>
      </li>
      <li class="nav-item" style="margin-left: 45em;">
          <a class="nav-link" href="#"style="margin-left: em;font-size: 18px;
		font-family: 'Cairo', sans-serif;float: left;"> Login |</a>
		  <a class="nav-link" href="#" style="margin-left:em;font-size: 18px;
		font-family: 'Cairo', sans-serif; float: left;">Register </a>
      </li>
      <!-- <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Login
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">Profile</a>
          <a class="dropdown-item" href="#">Check Status</a>
          <a class="dropdown-item" href="#">Transaction History</a>
          <a class="dropdown-item" href="#">Log out</a>
        </div>
      </li> -->
      
    </ul>
  </div>
</nav>

<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" style="position: relative; ">
  <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="images/Food-Stands-at-Summer-Festival-in-Japan.jpg" style="height: 500px;" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="images/maxresdefault.jpg" style="height: 500px;" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="images/Ohio_State_Fair_Picture_1_0.jpg" style="height: 500px;" alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

<div class="middle-1">
	<p class="middle-1-title" style="color: #ff5416;text-align: center;margin-top: 5%;font-size: 3em;font-weight: bold;">How It Works</p>
	<br>
	<div class="container-fluid">
		<div class="row">
		    <div class="col-md-4" >
		    	<p><button class="btn-number">1</button> Select Event</p>
		    </div>
		    <div class="col-md-4">
		    	<p><button class="btn-number">2</button> Find Stall </p>
		    </div>
		    <div class="col-md-4">
		    	<p><button class="btn-number">3</button> Rent</p>
		    </div>
		</div>
	</div>
	<br>
	<br>
    <br>
	<div class="container-fluid"style="background-color: #f7f2f2;">
		<div class="row" style="margin-left: 2.5%;">
		    <div class="col-md-4" >
		    	<p><button class="btn-number">4</button> Waiting For Approval</p>
		    </div>
		    <div class="col-md-4">
		    	<p><button class="btn-number">5</button> Make Payment</p>
		    </div>
		    <div class="col-md-4">
		    	<p><button class="btn-number">6</button> Done !</p>
		    </div>
		</div>
	</div>
</div>

<br>

<div class="middle-2" style="background-color: #ff5416;margin-top: 6%;">
	<p class="middle-2-title" style="color: #f7f2f2;text-align: center;margin-top: 5%;font-size: 3em;font-weight: bold;">Benefits</p>
	<div class="container-fluid">
		<div class="row">
			<div class="col-md-4">
				<i class="fas fa-map-marker-alt" style="text-align: center;font-size: 500%;"></i>
				<br><br>
				<p style="font-weight: 600;">Strategy location</p>
			</div>
			<div class="col-md-4">
				<i class="fas fa-handshake" style="text-align: center;font-size: 500%;"></i>
				<br><br>
				<p style="font-weight: 600;">Trusty</p>
			</div>
			<div class="col-md-4">
				<i class="fas fa-store-alt" style="text-align: center;font-size: 500%;"></i>
				<br><br>
				<p style="font-weight: 600;">More Option</p>
			</div>
		</div>
	</div>
</div>
<div class="footer" style="background-color: #47413e;">
	<div class="container-fluid">
		<div class="row">
			<div class="col-md-8">
				<p style="font-size: 1em;margin-top: 6%;color: #f7f2f2;">&copy2019 JUST RENT | <a href="#" style="color: #f7f2f2;;font-size: 1em;">Privacy Policy</a> | 
					<a href="#" style="color: #f7f2f2;font-size: 1em;">Terms</a></p>
			</div>
			<div class="col-md-4">
				<p style="color: #f7f2f2;">Follow us on:</p>
				<a href="#" style="color: #1877f2;"><i class="fab fa-facebook" style="font-size: 250%;"></i></a>
				<a href="#" style="color: #c32aa3;"><i class="fab fa-instagram" style="font-size: 250%;"></i></a>
				<a href="#" style="color: #ff0000;"><i class="fab fa-youtube" style="font-size: 250%;"></i></a>
				<a href="#" style="color: #1da1f2"><i class="fab fa-twitter" style="font-size: 250%;"></i></a>
			</div>
		</div>
	</div>
		
			
</div>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    </div>
  </body>
</html>
