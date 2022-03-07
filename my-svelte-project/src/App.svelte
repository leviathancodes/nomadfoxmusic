<script>
	import * as data from './appdata.json';
	import { Button } from 'carbon-components-svelte';
	import 'carbon-components-svelte/css/g100.css';

</script>


<body>
	<div class="eduardo">
		<h1>{data.title}</h1>
		<a href={data.featured.latestMusic.link}>
			<Button isSelected class="link" kind="tertiary">
				{data.featured.latestMusic.title}
			</Button>
		</a>
	</div>
</body>


		<style>

			.eduardo {
				display: flex;
				flex-direction: column;
  align-items: center;
  justify-content: center
			}
		</style>
