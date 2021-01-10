<script>
	import Nav from "../components/Nav.svelte";
	export let segment;
</script>

<style>
	:global(body) {
		background-color: #303253;
	}
	:global(h1, h2, h3, h4, h5) {
		color: white;
	}

	main {
		position: relative;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>

<Nav {segment} />

<main>
	<slot />
</main>
