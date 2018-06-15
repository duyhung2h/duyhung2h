<!DOCTYPE html>
<html>
	<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<link rel="icon" href="icon.jpg">

		<title>Homepage</title>
		<style>
		
body, html {
    height: 100%;
	width: 100%;
    margin: 0;
	font-family: "Impact", Charcoal, sans-serif;
}
				


.bg {
    /* The image used */
    background-image: url("bg.jpg");
	background-color: #c92727;

    /* Full height */
    height: 100%; 
	width: 100%;

    /* Center and scale the image nicely */
    background-position: absolute;
    background-repeat: no-repeat;
    background-size: cover;
}

			
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
	width: 100%;
    background-color: #e6e6e6;
    position: -webkit-sticky; /* Safari */
    position: sticky;
    top: 0;
}

			
.headernav {
    list-style-type: none;
    margin: 0;
    overflow: hidden;
	width: 60%;
    align: left;
    background-color: rgba(255, 255, 255, .0);
	border: 2px solid gray;
	border-bottom: 0;
    position: static;
    top: 0;
	margin-right: 20%;
	margin-left: 20%;
}


aside {
    list-style-type: none;
    width: 31%;
	border: 2px solid gray;
	//height: 620px;
	overflow: hidden;
	padding: 2% 2%;
    float: left;
	//margin-left: 2%;
    background-color: rgba(255, 255, 255, .5);
	color: #737373;
	
	
	font-family: "Ariel", Charcoal, sans-serif;
	
}

			li {
			    float: left;
			}
			li2 {
				width: 10%;
			    float: left;

			}

			li a {
			    display: block;
			    color: #ff0000;
			    text-align: center;
			    padding: 1px 11px;
			    text-decoration: none;
			}
			
			
			.active2	{
			    background-color: #8c8c8c;
			    color: #ffffff;
			    float: left;
				position: absolute;
				text-align: center;
				width: 47.9%;
				height: 60px;	
			}
			
			
			li2 a {
			    display: block;
			    color: #ffffff;
			    text-align: center;
				height: 60px;
			    text-decoration: none;
			}
			
			center	{
				left: 0;
				padding-top: 20px;
				width: 100%;
				text-align: center;
				font-size: 18px;
			}
			
			
			li2.rightside	{
				float: right;
			}
			

			li a:hover:not(.active) {
			    background-color: #ff3333;
			    color: #ffffff;
			}
			
			
			li2 a:hover:not(.active2) {
			    background-color: #ffffff;
			    color: #000000;
			}
			
			

			.active {
			    background-color: #ff0000;
			    color: #ffffff;
			}
			
			

			.main-body {
			    border: 2px solid gray;
				//margin-right: 2%;
				//height: 620px;
				padding: 2% 2%;
				width: 60%;
				float: right;
				Text-align: left;
				background-color: rgba(255, 255, 255, .5);
				
				
				font-family: "Times-new-roman", Charcoal, sans-serif;
			}


			.banner {
				margin-right: 27%;
				margin-left: 27%;
				text-align: center;
				margin-bottom: 1%;
				background-size: 100%;
				padding: 1px;
				border: 4px;
				border-color: #ffffff;
				border-style: dotted;
				border-radius: 8px;
				font-size: 14px;
				color: #ffffff;
			}
			
			.footer		{
				background-color: #e9ef2b;
				text-align: center;
				background: url(bg2.jpg) no-repeat;
				background-size: 100%;
				left: 50%;
				padding: 5px;
				font-size: 20px;
				font-weight: bold;
				clear: both;
			}

header {
    clear: left;
    text-align: center;
}


img {
    width: 80%;
    opacity: 0.8;
    //height: 80%;
}


img:hover {
    opacity: 1.0;
    filter: alpha(opacity=100); /* For IE8 and earlier */
}


.search-container button:hover {
  background: #ccc;
}


.ul .search-container button {
    float: right;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  
  
.ul  .search-container {
    float: right;
  }



p	{	
	font-weight: bold;
	text-decoration: none;
    opacity: 0.5;
	color: #000000;
	padding-bottom: 2%;
}


a	{	
	text-decoration: none;
	color: #000000;
}


p:hover	{	
	text-decoration: underline;
    opacity: 1;
}

p.boarder	{
	padding: 2%;
    border-top: double;
	border-top-color: solid gray;
    opacity: 1;
}

p.text	{
	text-decoration: none;
}

p.nopadding	{
	padding-bottom: 0px;
    margin-top: 0;
    margin-bottom: 0;
    margin-left: 0;
    margin-right: 0;
	display: inline;
}

b	{	
	font-size: 30px;
}




.logo	{
	opacity: 1;
    width: 30%;
}
  
		</style>
	</head>
<body class="bg">
	<ul>
	  <li><a class="active">HOMEPAGE</a></li>
	  <li><a href="topics.html">TOPICS</a></li>
	  <li><a href="articles.html">ARTICLES</a></li>
	  <li><a href="sites.html">SITES</a></li>
	  
		<div class="search-container" style="float:right">
			<form action="/homepage.html">
			<input type="text" placeholder="Search.." name="search">
			<button type="submit"><i class="fa fa-search"></i></button>
			</form>
		</div>
  
	</ul>
<header>
	<img class="logo" src="homelogo.jpg">
</header>

	<div class="banner">"Welcome to my webpage! This is a class project for a website which covers video-gaming related news."</div>
	
	
	
	
	
	
	
	
	
	<ul class="headernav">
	  <li2><a href="homepage.html"><center><</center></a></li2>
	  <li2><a class="active2"><center>HOMEPAGE (PAGE #1)</center></a></li2>
	  <li2 style="float:right"><a href="homepage2.html"><center>></center></a></li2>
	</ul>
	
	
	
	
	
	
	<aside>
	
	<b>You</b> may also like:
	<p></p>
	<p></p>
	<p></p>
	<a href="https://touhouprojectlovers.blogspot.com/"><img src="touhou.jpg"></a>
	<p><a href="https://touhouprojectlovers.blogspot.com/">Download Touhou official games:</a></p>
		<p></p>
			<p></p>
		<p></p>
			<p></p>
	
	
	<a href="https://www.reddit.com/"><img src="reddit.jpg"></a>
	<p><a href="https://www.reddit.com/">Reddit.com: The front page of the internet.</a></p>
	<p class="text">Reddit gives you the best of the internet in one place. 	Get a constantly updating feed of breaking news, fun stories, pics, memes, and videos just for you.</p>
	
		<p></p>
			<p></p>
		<p class="boarder"></p>
	
	<p class="text"><b>ADVERTISEMENT:</b></p>
		<p></p>
			<p></p>
	
	<a href="https://touhouprojectlovers.blogspot.com/"><img src="warframe.jpg"></a>
	<p><a href="https://touhouprojectlovers.blogspot.com/">"Ninjas play free". Download Warframe, an Action Online Third-Person Shooter game:</a></p>
	<p></p>
		<p></p>
			<p></p>
	
	<a href="https://kotaku.com/"><img src="kotaku.jpg"></a>
	<p><a href="https://kotaku.com/">Kotaku, a mainstream news outlet related to gaming in general:</a></p>
		<p></p>
		<p></p>
			<p></p>
			
	
		<p class="boarder"></p>
		
		
	<p class="text">This website has been supported by:</p>
	
	
	<a href="https://www.w3schools.com/default.asp"><img src="w3schools.jpg"></a>
	<p><a href="https://www.w3schools.com/default.asp">W3schools, by teaching me about HTML in general.</a></p>
	<p class="text">...And my wonderful teacher: Le Phuong Chi.</p>
	
	
	</aside>

	
	
	
	
	
	
	<div class="main-body">
	
	<p><a href="articles.html"><b>New <i>pokémon</i>  game have been announced for Switch!</b></a></p>
	<a href="articles.html"><img src="pokemonswitch.jpg"></a>
	<p class="text">Let’s Go Pikachu and Let’s Go Eevee are real, and coming to the Switch on November 16, Nintendo announced this evening, confirming previous leaks and rumors.</p>
	<p class="boarder"></p>
	
	<p><a href="articles2.html"><b>Analysis of stealth gameplay in Warframe</b></a></p>
	<a href="articles2.html"><img src="stealth.jpg"></a>
	<p class="text">“Ninjas Play Free” — The tagline boasted at the end of the Warframe cinematic trailer invokes a sense of eastern allure with a promise of ninja-like gameplay with the powerful characters shown in the cinematic footage of warframes on the battlefield. The mastery of martial arts and powerful abilities is prominent in the design of the game, though it does not take long to realize that there is very little offered in regards to the stealth component of being a ninja in Warframe. Over the years, Digital Extremes has made several improvements and adjustments to stealth gameplay, but ultimately it is an underwhelming aspect of gameplay which is quickly ignored in favor of more brute force tactics.</p>
	<p class="boarder"></p>
	
	<p><a href="articles4.html"><b>The man who inspired Snorlax</b></a></p>
	<a href="articles4.html"><img src="snorlax.jpg"></a>
	<p class="text">“One of the most beloved Pokémon is Snorlax. Meet the man who inspired the character.</p>
	<p class="boarder"></p>
	
	</div>

	<div class="footer">
		Copyrights and other stuffs goes here.
		<p class="nopadding"></p>
		©Web maker: Nguyen Duy Hung a.k.a duyhung2h, <p class="nopadding"><a href="https://www.facebook.com/hung.nguyenduy.5">Facebook</a></p>, <p class="nopadding"><a href="https://duyhung2h.deviantart.com/">DeviantArt</a></p>, <p class="nopadding"><a href="https://www.youtube.com/channel/UCeClBZG-LQWVmxb0rGo2Qbw">Youtube</a></p>
	</div>
   
</body>

</html>
