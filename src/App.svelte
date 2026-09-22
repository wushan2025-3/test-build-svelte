<script>
	let count = 0;

	function increment() {
		count += 1;
	}
</script>

<main>
	<h1>Hello Svelte!</h1>
	<p>This is a Svelte app built with Rollup.</p>
	<button on:click={increment}>
		Count: {count}
	</button>
</main>

<style>
	:global(body) {
		font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
		margin: 0;
		padding: 20px;
		background: #f9f9f9;
	}
	main {
		text-align: center;
	}
	h1 {
		color: #ff3e00;
	}
	button {
		font-size: 1.2rem;
		padding: 10px 20px;
		cursor: pointer;
	}
</style>
