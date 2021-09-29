<script>
	export let name;
</script>

<main>
	<h1>Uwu ur {name}!</h1>
	<p>
		<a href="https://svelte.dev/tutorial">Cum</a> well daddyy~❤️ I'm waiting
		for you to spurts lots and lots of your thick and tasty milk ❤️❤️❤️
	</p>
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
