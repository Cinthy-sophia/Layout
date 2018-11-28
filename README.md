```html
<!DOCTYPE html>
<html>
<head>
	<style type="text/css">

		#outer{
			display: inline-block;
			width: 100%;
			margin: 0px auto;
			background-color: white;
		}

		#logo{
			display: inline-block;
			width: 20%;
			border: 1px solid black;
			

		}

		#topic{
			display: inline-block;
			width: 20%;
			border: 1px solid black;


		}
		#header{
			display: inline-block;
			width: 56%;
			
		}
		#search {
		    text-align: right;
		    border: 1px solid black;
		    margin-right: 0px;
		    width: 100%;
		}
		#info{ 
			width: 80%;
			text-align: right;
			border: 1px solid black;

		}
		#derecho{	
			margin-left: 13px;

		}
		#izquierdo{
			height: 500px;


		}
		#contenido {
			display:inline-block;

		}
		body {
			margin:0px;
		}
		p{
			margin-top: 0px;
		}
		nav {
			display: inline-block; 
			text-align: center;
			width: 100%;
			border: 1px solid black;

		}

		li {
		    display: inline;
		    border: 1px solid black; 
		}
		
		header {
			text-align: center;
			width:100%;
			height:120px;
			border: 1px solid black; 
		} 

		aside {
			display: inline-block;
			width:20%;
			height:500px;
			border: 1px solid black;
			vertical-align: top;
			
		} 

		section {
			display: inline-block;
			width:58%;
			height: 500px;
			border: 1px solid black;
			
		}
		footer{
			display: inline-block;
			width: 100%;
			height:100px;
			border: 1px solid black; 
    		margin-top: 12px;
    		

		}

	</style>

	<title>Layout</title>

</head>

<body>

	<div id="outer"> 
		
		<header>

			<div id="logo"> Logo </div>
			<div id="header" >Header</div>
			<div id="topic">

				<ul id="menu_secundario"> 
					Topic 1
					Topic 2
					Topic 3
					Topic 4
				</ul>

			<div id="search">Search</div>

			</div>

		</header>

		<nav>

			<ul>

				<li>INICIO</li>
				<li>GALERIA</li>
				<li>UBICACION </li>
				<li>CONTACTO</li>

			</ul>

		</nav>

		<div id="contenido">
			
			<aside id="izquierdo">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
			</aside>

			<section>

			<div align="center"><img src="https://www.mercurynews.com/wp-content/uploads/2017/12/dog-junie_-bro-jorgensen.jpg" width="485px"></div>

				<p>
					Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
				</p>

			</section>

			<aside id="derecho">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</aside>
			

			
			
		</div>

		<footer>  
			COPYRIGHT
			ENLACES DE INTERES


		</footer>

	</div>

</body>

</html>
```
