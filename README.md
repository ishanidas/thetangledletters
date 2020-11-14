<!doctype html>
<html>
<head>
<title>the_tangled_letters</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lobster&effect=brick-sign">
<style>
	body	{
				text-align: center;
				background-image: url('https://i.pinimg.com/originals/f9/5a/c3/f95ac3ca16b960eb6deb14d9935fd8f4.jpg');
				width:1100 px;
				color:white;
				max-width:95%;
				margin:auto;
			}
	.imga {	width: 50%;
				border: 5px solid white;
			}
	.headfile {
					margin: 1em 0 0.5em 0;
					color: white;
					font-weight: normal;
					font-family: "Comic Sans MS", cursive, sans-serif;   
					font-size: 44px;
					line-height: 42px;
					text-transform: uppercase;
					text-shadow: 0 2px black, 0 3px #777;
					border: 5px solid white;
			}
	.input	{
					background-color: white;
					border: 2px solid white;
					border-radius: 20%;
					margin: 4px 2px;
					input: solid white;
					input-font-family: Arial;
					padding: 5px 30px;
				}
	.button {
					background-color: transparent;
					border: 5px solid white;
					border-radius: 20%;
					color: white;
					padding: 15px 32px;
					text-align: center;
					font-family: Arial ;
					display: inline-block;
					font-size: 20px;
					margin: 4px 2px;
					cursor: pointer;
				}
	.quote	{
					font-family: "Lobster", Sans-serif;
					font-size: 36px;
			}
	.quo	{
					font-family: "Lobster", Sans-serif;
					font-size: 36px;
					border: 5px solid white;
					display: table;
					margin: 0px auto 0px auto; 
					padding:5px;background-color:black;color:#ffffff;
			}
	.para	{
					font-family: "Lobster", Sans-serif;
					font-size: 36px;
					border: 5px solid white;
					display: table;
					margin: 0px auto 0px auto; 
					padding:5px; background-color: white;color:#000000;
			}
	.mySlides {display:none;}
</style>
</head>
<body>
		<h1 class="headfile"> The Tangled Letters </h1>
	<Br/><Br/>
	<script>
	function addParagraphText()
	{
		var x=document.getElementById("name").value;
		if(x.length==0)
		{
				document.getElementById("demo").innerHTML="Lemme know your name please :)";
		}
		else
		{
				document.getElementById("demo").innerHTML="Hello "+x+"! Welcome to the tangled letters: Adorned with thy existence, in search of the true realm."+"<br>"+"Embark on a journey with me, where you'll encounter life with new meanings and shades. Glad you are here :)";
		}
	}
</script>
	<div class="quote">
		<p>"Your voice may fail, Your letters never"</p>
		<pre class="quote">			-The Tangled Letters</pre>
	</div>
	<Br/><Br/>
	<h1><i>WHO ARE YOU? The name you wanna give to yourself but you gotta a different one, can be the same too! Type in the curvy box below.</i><h1>
	<Br/>
	<input class="input" id="name" type="text"/>
	<button class="button" onclick="addParagraphText();">Tap Me!</button>
	<Br/><Br/><Br/>
	<p class="quo" id="demo"></p>
	<Br/><Br/>
	</div>
	<h2 class="quo">Few of the Creations! Please Click on the right, left arrows! :)</h2>
	<Br/>
	<div class="w3-content w3-display-container">
  <img class="mySlides" src="https://lh3.googleusercontent.com/XKWHAL8DDCKYUW76zNQLb_0FwqmjXwwD1jtxPAWTuq1iwEjoqqfnC32FSKSFFz_2Om0o6UpfIRuxTNE-nzEkSTNO6BOIW2ZUPlozGQFyNwF_V955Ik0b84fzp761UlKFZ28eItWwEQ=w2400" style="width:100%"></img>

  <img class="mySlides" src="https://lh3.googleusercontent.com/WlTaoYbaP3ujCxLI1xU-Glksr3n358wf76lCVKxvBqDYvkrOGNwGlUsvNJiq8udGa1mwHQ4IhreN13-3pNC-7w6OBQHcTSfZ1ucvnCT5qUiN-IWJLoFAH7NF5boDs3qjvycGdIrTdQ=w2400" style="width:100%"></img> 
  <img class="mySlides" src="https://lh3.googleusercontent.com/0cV6xUNmN5fMNCJGUEXvqOVTvs0T0-3EKAehL_Uovpo3jMdzGMx4jSWxi48obMad8r0Ew0XToGcdNvt_tlJPFreaGSZKEgNY-vNcW744YxHCuFPUmmdeUMN9g7OWmWLu-q6iisvOGA=w2400" style="width:100%"></img>
  <img class="mySlides" src="https://lh3.googleusercontent.com/N9g2V2Jd1gRFX43abQGEpKeDwjuSx9-cNPeLfHxsZBc5X4OCCz2h6riBrW9MU7ui7ivXWXBNGroNQeQmtqwaHE2v_Xz6zwEOXeWS-MtDxjb3jOBaibnXJpZ_Q9jPj91XlhGxIiHflQ=w2400" style="width:100%"></img>

  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>
<Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/>
<h1 class="quo">All that my heart speaks................!:)</h1>
<Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/>
<table>
	<tr>
    <td><img class="imga" src="https://lh3.googleusercontent.com/5d4B03BhqLkIwB0Gv2xlLy3iVWvY7GZLY9uZCd2MhqqZTMowVvAUJRo8-kSULjAAN6X9tTM2L5aDWTK2fup4760AwYxoyFVl4Kved480Nd24eXfdz-aHa4bkmDbNauPWZEzXPwT0aw=w2400" style="width:80%"/><Br/><p class="para">Have you ever thought why sometimes you just change so much even without acknowledging your own conscience?</p></td>
    <td><pre>		</pre></td>
	<td><pre>		</pre></td>
	</tr>
	<Br/>
	<tr>
	<td><pre>		</pre></td>
	<td><pre>		</pre></td>
	<td><img class="imga" src="https://lh3.googleusercontent.com/8elTw5avx0kYLJ00koMB67ax1xatyW64Dl2Ril4ECPMNy81f55KkVj_Pm4ikBnZgDPs9iIWecVlchOJ06Q3otovcE-_YWZPx3dxBixIBORbzbolncK3JDOrAUnTq-koFpm2X6yD_jA=w2400" style="width:40%"/><Br/><p class="para">The String theory states that all the tiniest particles are just the result of the different patterns of vibration of tiny strings of energy, already depicting the messiness of the universe in this theory of everything...</p></td>
  </tr>
	<Br/>
	<Br/>
	<tr>
    <td><img class="imga" src="https://lh3.googleusercontent.com/gWRFEHWNMbm9ssASsNzO1tUne3Krz08dl9skbuLIc9oyCkrNkBtk8AHV4OHDMhsRE5o7UFVChYH7H-49Ua8EbUisoSYcw-bx3k9O1H4qcYXHIs9a5z4pjQ6Et2G80xBj6SZJGme89w=w2400" style="width:80%"/><Br/><p class="para">Time is relative, it bends with space, that's queer, yet it teaches us some brilliant precepts..!</p></td>
    <td><pre>		</pre></td>
	<td><pre>		</pre></td>
	</tr>
</table>
<Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/><Br/>
<h1 style="font-family: Arial;">Check The Tangled Letters on Instagram! Click on the pink cam -> <a href="https://www.instagram.com/a_lost_comet/">
		<img alt="Instagram" src="https://assets.stickpng.com/images/580b57fcd9996e24bc43c521.png" width="50" height="50">
		</a></h1>
	 
</body>
</html>
