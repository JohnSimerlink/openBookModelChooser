<script>

	import ModelChooser from './ModelChooser.svelte'
</script>

<main>
  <ModelChooser></ModelChooser>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		/*max-width: 240px;*/
		margin: 0;
		width: 100%;

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
	main {
		margin: 0 auto;
	}
</style>
