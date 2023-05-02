# notion_widgets
A set of HTML widgets that could be embedded into [Notion.so](https://www.notion.so/) pages.
[learn more](https://blog.shorouk.dev/notion-widgets-gallery/)
<!DOCTYPE html>
<html>

<head>

	<!-- Font Awesome -->
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">

	<!-- Google Font -->

	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Lato:wght@700&display=swap" rel="stylesheet">

	<!-------->

	<style>
		* {
			margin: 0;
			padding: 0;
			-webkit-box-sizing: border-box;
			box-sizing: border-box;
		}


		.navMenu {
			font-family: 'Advent Pro', sans-serif;
			padding: 8px;
			text-align: center;
			margin: 7px auto;
			width: fit-content;
		}

		.navMenu a {
			color: #272727;
			text-decoration: none;
			text-transform: uppercase;
			display: inline-block;
			padding: 6px;
		}

		.background {
			background-color: #f89cc4;
		}

		.border {
			border: 1px solid #cccccc;

		}

		.navMenu a:hover {

			color: #d09c0b;
		}
	</style>
</head>

<body>

	<nav class="navMenu  border background">
		<a id="home" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-house"></i> Home</a>
		<a id="inbox" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-inbox"></i> Inbox</a>
		<a id="week" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-calendar-week"></i> Planner</a>
		<a id="projectos" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-briefcase"></i> Projectos</a>
            <a id="agenda" onclick="navigate(this.id)" href="#"> <i class="fa-regular fa-calendar-days"></i> Agenda</a>
		<a id="tarefas" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-list-check"></i> Tarefas</a>
		<a id="negócios" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-money-bill-wave"></i> Negócios</a>
		<a id="estudo" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-notebook"></i> Estudo</a>
		<a id="tópicos" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-layer-group"></i> Tópicos</a>
		<a id="notas" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-book"></i> Notas</a>
		<a id="media" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-bookmark"></i> Media</a>
		<a id="recursos" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-wrench"></i> Recursos</a>
		<a id="lifewiki" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-heart"></i> Lifewiki</a>
		<a id="receitas" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-hat-chef"></i> Receitas</a>
		<a id="lista" onclick="navigate(this.id)" href="#"> <i class="fa-sharp fa-solid fa-list"></i> Lista</a>


	</nav>


	<script>

		let direction = "horizontal";
		if (direction === "vertical") {
			document.head.insertAdjacentHTML("beforeend", `<style>.navMenu a {display: block; text-align:left; margin:7px} i{width:15px; margin-right:5px} .navMenu{margin:3px}</style>`)
		}


		function navigate(id) {

			if (id == 'home')
				window.open("https://example.com", '_blank').focus();
			else if (id == "inbox")
				window.open("https://example.com", '_blank').focus();
			else if (id == "week")
				window.open("https://example.com", '_blank').focus();
			else if (id == "month")
				window.open("https://example.com", '_blank').focus();
			else if (id == "projects")
				window.open("https://example.com", '_blank').focus();
			else if (id == "business")
				window.open("https://example.com", '_blank').focus();
			else if (id == "tasks")
				window.open("https://example.com", '_blank').focus();
			else if (id == "knowledge")
				window.open("https://example.com", '_blank').focus();
			else if (id == "topics")
				window.open("https://example.com", '_blank').focus();
			else if (id == "notes")
				window.open("https://example.com", '_blank').focus();
			else if (id == "media")
				window.open("https://example.com", '_blank').focus();
			else if (id == "resourses")
				window.open("https://example.com3", '_blank').focus();
			else if (id == "lifewiki")
				window.open("https://example.com", '_blank').focus();

		}
	</script>


</body>

</html>
