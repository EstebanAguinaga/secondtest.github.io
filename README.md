<!DOCTYPE html>
<html>

<head>
<title>Tron Legacy</title>
	<meta name="author" content="Esteban Aguinaga">
	<meta charset="utf-8">
	<meta name="viewport" content="user-scalable=no, width=device-width">
    
<!-- "https://img3.goodfon.com/wallpaper/nbig/7/b0/tron-tron-nasledie-gorod.jpg" is the image used for the original background, in case you use it for an image later if you coninue with the first movie idea 

"https://cdn.dribbble.com/users/648922/screenshots/4952788/cyberpunk.png" is a flat-design cyberpunk image for later (after days of searching, this is the one).

.transB1{
    background-color: rgba(0, 0, 0, 0.5); /* Black background with 50% opacity */
    border-color: rgb(230, 0, 0);
    padding: 10px;
    border-width: 18px;
    border-style: double;
    margin-top: 24px;
}

.transB2{
    background-color: rgba(0, 0, 0, 0.5); /* Black background with 50% opacity */
    border-color: rgb(230, 0, 0);
    padding: 10px;
    border-width: 18px;
    border-style: double;
    margin-top: 24px;  
}

^^^that was the original border 1 and 2 CSS just in case

style="padding-top: 3000px; margin-top: -3000px; padding-left: 3000px; margin-left: -3000px; padding-right: 3000px; margin-right: -3000px; padding-bottom: 3000px; margin-bottom: -3000px;"

^^^that is to make the element extend fully - edit as you please

-->
    
<link href='https://fonts.googleapis.com/css?family=Orbitron' rel='stylesheet'>
<link href='https://fonts.googleapis.com/css?family=Barlow|Tomorrow' rel='stylesheet'>
<link href='https://fonts.googleapis.com/css?family=Varela' rel='stylesheet'>
<link href='https://fonts.googleapis.com/css?family=Audiowide' rel='stylesheet'>
	<style>

.glitch{
    font-family: "Varela", sans-serif;
    color: yellow;
    position: relative;
    left: -3;
    margin: 0;
    width: 50%;
    background-size: contain;
    padding: 0;
}

.glitch2{
    font-family: "Audiowide", sans-serif;
    color: orange;
    left: 5%;
    margin: 0;
    width: 100%;
    background-size: contain;
    padding: 0;
    font-size: 64px;
    position: absolute;
    top: 110%;
}

@keyframes noise-anim {
  0% {
    clip-path: inset(10% 0 7% 0);
  }
  5% {
    clip-path: inset(57% 0 14% 0);
  }
  10% {
    clip-path: inset(4% 0 54% 0);
  }
  15% {
    clip-path: inset(89% 0 10% 0);
  }
  20% {
    clip-path: inset(24% 0 42% 0);
  }
  25% {
    clip-path: inset(68% 0 2% 0);
  }
  30% {
    clip-path: inset(60% 0 18% 0);
  }
  35% {
    clip-path: inset(43% 0 55% 0);
  }
  40% {
    clip-path: inset(84% 0 15% 0);
  }
  45% {
    clip-path: inset(42% 0 16% 0);
  }
  50% {
    clip-path: inset(79% 0 15% 0);
  }
  55% {
    clip-path: inset(29% 0 44% 0);
  }
  60% {
    clip-path: inset(90% 0 1% 0);
  }
  65% {
    clip-path: inset(24% 0 8% 0);
  }
  70% {
    clip-path: inset(91% 0 8% 0);
  }
  75% {
    clip-path: inset(96% 0 2% 0);
  }
  80% {
    clip-path: inset(82% 0 19% 0);
  }
  85% {
    clip-path: inset(14% 0 44% 0);
  }
  90% {
    clip-path: inset(30% 0 19% 0);
  }
  95% {
    clip-path: inset(54% 0 45% 0);
  }
  100% {
    clip-path: inset(62% 0 31% 0);
  }
}

.glitch::after{
    content: attr(data-text);
    position: absolute;
    left: 2px;
    text-shadow: -3px 0 red;
    top: 0;
    color: yellow;
    background: none;
    overflow: hidden;
    animation: noise-anim 2s infinite linear alternate-reverse;
}

.glitch2::after{
    content: attr(data-text);
    position: absolute;
    left: 2px;
    text-shadow: -3px 0 pink;
    top: 0;
    color: orange;
    background: none;
    overflow: hidden;
    animation: noise-anim 2s infinite linear alternate-reverse;
}

@keyframes noise-anim-2 {
  0% {
    clip-path: inset(88% 0 10% 0);
  }
  5% {
    clip-path: inset(29% 0 71% 0);
  }
  10% {
    clip-path: inset(40% 0 31% 0);
  }
  15% {
    clip-path: inset(52% 0 31% 0);
  }
  20% {
    clip-path: inset(80% 0 17% 0);
  }
  25% {
    clip-path: inset(61% 0 37% 0);
  }
  30% {
    clip-path: inset(97% 0 2% 0);
  }
  35% {
    clip-path: inset(95% 0 6% 0);
  }
  40% {
    clip-path: inset(55% 0 2% 0);
  }
  45% {
    clip-path: inset(76% 0 17% 0);
  }
  50% {
    clip-path: inset(54% 0 13% 0);
  }
  55% {
    clip-path: inset(88% 0 5% 0);
  }
  60% {
    clip-path: inset(26% 0 48% 0);
  }
  65% {
    clip-path: inset(68% 0 2% 0);
  }
  70% {
    clip-path: inset(84% 0 7% 0);
  }
  75% {
    clip-path: inset(55% 0 37% 0);
  }
  80% {
    clip-path: inset(2% 0 29% 0);
  }
  85% {
    clip-path: inset(25% 0 47% 0);
  }
  90% {
    clip-path: inset(42% 0 7% 0);
  }
  95% {
    clip-path: inset(20% 0 1% 0);
  }
  100% {
    clip-path: inset(23% 0 58% 0);
  }
}

.glitch::before{
    content: attr(data-text);
    position: absolute;
    left: -2px;
    text-shadow: 1px 0 blue;
    top: 0;
    color: yellow; 
    background: none;
    overflow: hidden;
    animation: noise-anim-2 15s infinite linear alternate-reverse;
}

.glitch2::before{
    content: attr(data-text);
    position: absolute;
    left: -2px;
    text-shadow: 1px 0 tomato;
    top: 0;
    color: orange; 
    background: none;
    overflow: hidden;
    animation: noise-anim-2 15s infinite linear alternate-reverse;
}

*{
    box-sizing: border-box;
    scroll-behavior: smooth;
    transition-timing-function: ease-in-out;
}

body{
    background-color: rgb(0, 0, 0);
}

p{
    color: white;
    font-family: sans-serif;
}

h1{
    background-color: yellow;
    margin-left: -10px;
    margin-right: -10px;
    margin-top: -4px;
    padding: 10px;
    font-family: "Orbitron", sans-serif;
    font-size: 36px;
    border-bottom-style: double;
    border-width: 6px;
    border-color: black;
}

.border1{
    background-color: yellow;
    border-color: black;
}
  
.borderclip{
    width: 230px;
    height: 60px; 
    border: 0;
    outline: none;
    background-color: black;
    cursor: pointer;
    position: relative;
    clip-path: polygon(92% 0, 100% 25%, 100% 100%, 8% 100%, 0% 75%, 0 0);
    transition-duration: 0.1s;
}

.borderclipcont{
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    top: 2px;
    left: 2px;
    right: 2px;
    bottom: 2px;
    background-color: yellow;
    clip-path: polygon(92% 0, 100% 25%, 100% 100%, 8% 100%, 0% 75%, 0 0);
    transition-duration: 0.1s;
    transition-timing-function: ease-in-out;
}

.borderclip:hover{
    background-color: yellow;
    color: yellow;
}

.borderclipcont:hover{
    background-color: black;
}

.yellowsection{
    background-color: yellow;
    background-size: cover;
    width: 100%;
}

.navbarH > ul{
    z-index: 3;
    list-style-type: none;
    margin: 0;
    padding: 10px;
    background-color: yellow;
    background-size: 100%;
    border-bottom-style: double;
    border-color: black;
    border-width: 6px; 
    font-family: "Orbitron", sans-serif;
}

.navbarH > ul > li{
    display: inline;
    font-family: "Orbitron", sans-serif;
}

.titlepic{
    position: relative;
    margin-left: -10px;
    margin-right: -10px;
    object-fit: cover;
    opacity: 0.6;
    margin-bottom: 0;
}

.cyberflat{
    position: absolute;
    left: 0;
    right: 0;
    top: 40%;
    width: 50%
    text-align: center;
    margin-left: 25%;
    margin-right: 25%;
}

li{
    font-family: "Orbitron", sans-serif;
}

.startpara{
    font-size: 24px;
    position: absolute;
    top: 110%;
}

.whatiscyberpic{
    position: relative;
    margin-left: -10px;
    margin-right: -10px;
    margin-top: -4px;
    opacity: 0.3;
}

.whatiscyberpic:hover{
    transition: opacity 0.2;
}

.whatiscyber{
    position: absolute;
    top: 125%;
    left: 5%;
    right: 5%;
    font-size: 32px;
    font-family: "Varela", sans-serif;
    text-shadow: -2px 0 black, 0 2px black, 2px 0 black, 0 -2px black;
}

    </style>
</head>

<body>

<section class="navbarH">
    <ul style="margin: -10px -10px 0 -10px; font-family: 'Orbitron', sans-serif;">
            <li><button class="borderclip" onclick="document.location='#cyberpunk'" style="font-family: 'Orbitron', sans-serif;">
                    <span class="borderclipcont">CYBERPUNK_</span>
                </button>
            </li>
            <li><button class="borderclip" onclick="document.location='#movies'">
                    <span class="borderclipcont" style="font-family: 'Orbitron', sans-serif;">MOVIES_</span>
                </button>
            </li>
            <li><button class="borderclip" onclick="document.location='#games'" style="font-family: 'Orbitron', sans-serif;">
                    <span class="borderclipcont">GAMES_</span>
                </button>
            </li>
            <li><button class="borderclip" onclick="document.location='#music'" style="font-family: 'Orbitron', sans-serif;">
                    <span class="borderclipcont">MUSIC_</span>
                </button>
            </li>
            
    </ul>
</section>

<section>
<div class="titlepic">
    <img src="https://free4kwallpapers.com/uploads/originals/2019/11/24/cyberpunk-city-wallpaper.jpg" alt="cyberpunk city title image" width="100%" height="650">
</div>
    <div class="cyberflat">
        <header>
            <div class="glitch" data-text="CYBERPUNK_" style="font-size: 100px;">CYBERPUNK_</div>
        </header>
    </div>
</section>
<section>
    <div>
        <img id="cyberpunk" class="whatiscyberpic"src="https://d1s0ws440m13mk.cloudfront.net/original/3X/f/f/ff9941a8effb33dc6410cf4c3db7de731eb68144.jpg" alt="cyberpunk explanation background" width="101.5%">
        <p class="glitch2" data-text="What is Cyberpunk?">What is Cyberpunk?</p>
        <br>
        <br>
        <br>
        <p class="whatiscyber">"Cyberpunk is a subgenre of science fiction in a distopian setting that tends to focus on a 'combination of low-life and high tech' featuring advanced technological and scientific achievements, such as artificial intelligence and cybernetics, juxtaposed with a degree of breakdown or radical change in the social order. Much of cyberpunk is rooted in the New Wave science fiction movement of the 1960s and 1970s, when writers like Philip K. Dick, Roger Zelazny, John Brunner, J. G. Ballard, Philip José Farmer and Harlan Ellison examined the impact of drug culture and technology while avoiding the utopian tendencies of earlier science fiction."</p>
    </div>
</section>
<div>
		<section class="movies">
		  <h1 class="title1" id="movies">MOVIES_</h1>
		  <p>Cyberpunk-style movies were first introduced with the film "Blade Runner" in 1988.</p>
		  <p>Try to make your own Title to grab the readers into your article</p>
		  <p>Don't forget to change the title inside the HEAD and take out any code with my name Mrs. Bell inside, make it your own.</p>
			<p><img src="https://upload.wikimedia.org/wikipedia/commons/a/ab/Patates.jpg" alt="Lighthouse image" style="float: left"></p>
		  <p>the picture above <strong>should be your own and does not have to follow copyright laws. </strong>.</p>
		  <p>Tell about IRMA in your own words you may change the header picture if you like, you must change the other photo.</p>
		  <p>You are using your web design skills that you know to show me .</p>
        </section>
        <section>
		  <p>You'll also learn basic things like:<br>
				how to use a simple text editor<br>
				how to copy and paste<br>
				how to create folders<br>
				how to store files and images that make up your website<br>
				how to preview web pages with a browser.</p>
			<p>You will learn how to create a website <strong>The Right Way, The First time!</strong> There are a lot of tutorials on the internet that teach you how to build websites. Use them and you'll most likely be rebuilding your website to keep up with the times.</p>
		  <p>Use this template, you'll get started right and you'll be ready to progress to some more advanced teaching aids.</p>
		</section>
	</div>
	
	<footer>
		<address>
		&copy; Copyright 2018 All Rights Reserved<a href="mailto:b@gmail.com"> Mrs .Bell </a>
		</address>
	</footer>
</body>
</html>
