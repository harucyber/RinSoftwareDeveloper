<!DOCTYPE html>
<html>
<!-- I do not know if I am shocked or disapointed that this took me 45 minutes-->

<head>
	<link href='https://fonts.googleapis.com/css?family=Lexend Deca' rel='stylesheet'>
	<style>
	html {
  height: 100%;
  width: 100%;
  background-color: lightblue;
  font-family: 'Lexend Deca', sans-serif;
  color: black;
}

#intro{
  width: 500px; 
  margin: auto;

  padding: 20px;
  border-style: solid;
  border-color: #B6C7D6;
  border-radius: 20px;
  background-color: #EAF0F6;

  /*This was from https://blog.hubspot.com/website/center-text-in-css#:~:text=To%20center%20text%20in%20CSS%2C%20use%20the%20text-align%20property,case-by-case%20basis.*/
}
#padding{
	margin-left:1%;
	margin-right:1%;
	margin-top:1%;
	margin-bottom:1%;
}

#pfp{
	height:42%;
	width:42%;
	float: left;
	margin-right: 1%;
}
#pin{
	height:25px;
	width:25px;
}

.logo{
	height:25px;
	width:25px;
	margin-left: 5%;
	margin-right: 5%;
}

#buttons{
	margin-top: 1%;
	margin-left: 1%;
	text-align: left;
}
button{
	background-color: lightskyblue;
    font-family: 'Lexend Deca', sans-serif;
	border-radius: 10%;
	
}

a{
	text-decoration: none;
	color:black;
}
button:hover{
	background-color:lightcyan;
}
</style>
</head>

<body>
	<div id="intro">
		<div id="padding">
			<h1>RinUnderscore</h1>
			<img src='assets/rinpfp.jpg' id="pfp">
			<h3>Rin • Ethan Y</h3>
			<h3><img src="assets/pin.png" id="pin">New York City</h3>
			<span>Rin is a independent software developer who participates in hackathons and writes programs to increase
				his problem solving skills and abilities! I look forward to working with you!</span>

			<div id="buttons">
				<button><a href="https://github.com/RinSoftwareDeveloper"><img src='assets/git.png'
						class="logo">Github</a></button>
				<button><a href="mailto:riuunderscoreofficial@gmail.com"><img src='assets/mail.png'
						class="logo">Email</a></button>
				<button><a href="discord.com/login"><img src='assets/discord-mascot.png' class="logo">Discord</a></button>
			</div>
		</div>
	</div>
</body>

</html>
