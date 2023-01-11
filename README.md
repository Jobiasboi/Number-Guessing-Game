<html>
<style>
	p{
		font-family:"Comic Sans MS";
		
	}

	h1{
		font-family:"Comic Sans MS";
	}

	body{
		background-color:lightgray;
	}

	button{
		background-color:lightgray;
	}

	hr{
		background-color:black;
	}
</style>
<body>
<center>
<hr>
<h1>Pick A Number Game <3</h1>
<hr>
<p>Answer: <span id="Answer">?</span></p>
<p>Guesses Left: <span id="Guesses">10</span></p>
<p>Help: <span id="Help">?</span></p>
<button onclick="reset()">
	Play
</button>
<button onclick="reveal()">
	Reveal Answer
</button>
<button onclick="guess()">
	Guess
</button>

<hr>
<p>[ ! ] If you hit Reveal Answer it'll start a new game [ ! ]</p>
</center>
</body>
<script type="text/javascript" src="script.js"></script>
</html>
