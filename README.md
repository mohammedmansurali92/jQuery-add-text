# jQuery-add-text
Some codding of jQuery
<script>
		function appendText(){
			var txt1= "<p>Textm</p>";
			var txt2 =$("<p></p>").text("Textm");
			var txt3 = document.createElement("p");
			txt3.innerHTML= "Textm";
			$("body").append(txt1,txt2,txt3);
		}
	</script>
	</head>
	<body>
   <p>This is a paragraph</p>
   <button onclick="appendText()">Append Text</button>
