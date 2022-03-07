<script>
	export let name;
	import * as data from './appdata.json';
	import { Button } from 'carbon-components-svelte';
</script>

<main>
	<body>
		<h1>{data.title}</h1>
	</body>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>