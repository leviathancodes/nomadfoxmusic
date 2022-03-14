<script>
	import * as data from './appdata.json';
</script>

<style>
	@import url('http://fonts.cdnfonts.com/css/akira-expanded');

	.pageContainer {
		width: 100%;
		display: flex;
		flex-direction: column;
	}

	h1 {
		justify-content: center;
		text-align: center;
		padding: 1em;
		font-family: 'Akira Expanded', sans-serif;
	}

	.imgContainer {
		display: flex;
		width: 100%;
		position: absolute; 
		bottom: 0;
		align-items: center;
		justify-content: center;
	}

	.linkContainer {
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.nomadMain {
		width: 50%;
		align-items: center;
		justify-content: center;
	}


	
</style>


<body>
	<div class="pageContainer">
		<div class="headingContainer">
			<h1>Nomads Never Die</h1>
		</div>
		<div class="linkContainer">
			<a class="buttonMain" href="https://nomadfox.bandcamp.com/album/nomads-never-die">
			Support The Mixtape
			</a>
		</div>
		<div class="imgContainer">
			<img class="nomadMain" src="assets/nomad1.png" alt="Nomad Fox with his eyes covered by a bright orange rectangle."/>
		</div>
</div>
</body>
