<script>
	
</script>

<main>
	<img src="https://seeklogo.com/images/S/svg-logo-A7D0801A11-seeklogo.com.png" alt="" align="left" width="64px">
	<img src="https://seeklogo.com/images/S/svg-logo-A7D0801A11-seeklogo.com.png" alt="" align="right" width="64px">
	<h1>Titolo</h1>

	<nav>
		<a href="javascript:window.open('https://www.google.com')" id="google" class="logo_link" title="Google">
			<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Google_%22G%22_Logo.svg/2048px-Google_%22G%22_Logo.svg.png" width="32px" alt=""/>
		</a>
		<a href="javascript:window.open('https://www.google.com')" id="google" class="barra" title="Google">Google</a>

		<a href="javascript:window.open('https://www.poste.it')" id="poste" class="logo_link" title="Poste Italiane">
			<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Logo_semplice_Poste_Italiane.svg/1200px-Logo_semplice_Poste_Italiane.svg.png" width="32px" alt=""/>
		</a>
		<a href="javascript:window.open('https://www.poste.it')" id="poste" class="barra" title="Poste Italiane">Poste Italiane</a>

		<a href="javascript:window.open('https://www.spotify.com')" id="spotify" class="logo_link" title="Spotify">
			<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/Spotify_logo_without_text.svg/768px-Spotify_logo_without_text.svg.png" width="32px" alt=""/>
		</a>
		<a href="javascript:window.open('https://www.spotify.com')" id="spotify" class="barra" title="Spotify">Spotify</a>

		<a href="javascript:window.open('https://www.netflix.com')" id="netflix" class="logo_link" title="Netflix">
			<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/75/Netflix_icon.svg/2048px-Netflix_icon.svg.png" width="32px" alt=""/>
		</a>
		<a href="javascript:window.open('https://www.netflix.com')" id="netflix" class="barra" title="Netflix">Netflix</a>

		<a href="javascript:window.open('https://www.amazon.it')" id="amazon" class="logo_link" title="Amazon">
			<img src="https://upload.wikimedia.org/wikipedia/commons/4/4a/Amazon_icon.svg" width="32px" alt=""/>
		</a>
		<a href="javascript:window.open('https://www.amazon.it')" id="amazon" class="barra" title="Amazon">Amazon</a>
	</nav>

	<p>
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptatem suscipit alias eum neque veniam necessitatibus quidem quam, debitis voluptas rem eligendi saepe possimus sit doloribus maxime. Doloremque porro libero suscipit.
	</p>

	<hr>

	<ul>
		<li>
			ciao
		</li>
		<li>
			pippo
		</li>
		<li>
			pluto
		</li>
	</ul>

</main>

<style>
	main{
    background: linear-gradient(to left, gray, black);
	}
	h1{
		font-size: 62px;
		margin-top: auto;
		text-align: center;
		font-weight: bold;
		font-family: 'Times New Roman', Times, serif;
		animation: colorchange 10s infinite;
	}
	@keyframes colorchange{
	0% { color: rgb(183, 0, 255); }
	50% { color: rgb(0, 0, 255); }
	100% { color: rgb(183, 0, 255); }
	}
	a{
		text-decoration: none;
	}
	a:hover{
		text-shadow: 0px 0px 5px white;   
	}
	nav{
		font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
		font-size: 28px;
		text-align: center;
		background-repeat: no-repeat;
		background-attachment: fixed;
	}
	#google{
		color: rgb(255, 102, 0);
	}
	#amazon{
		color: rgb(0, 238, 255);
	}
	#spotify{
		color: rgb(2, 182, 2);
	}
	#netflix{
		color: red;
	}
	#poste{
		color: yellow;
	}
	.barra{
		margin-right: 50px;
	}
	.logo_link:hover{
		border: 1px solid;
	}
	p{
		font-size: 32px;
		color: white;
		padding: 3%;
	}
	hr {
	border: none;
	border-top: 3px double white;
	color: white;
	overflow: visible;
	text-align: center;
	height: 5px;
	}
	hr:after {
		background: none;
		content: '§';
		padding: 0 5px;
		position: relative;
		top: -13px;
	}
</style>