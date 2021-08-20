<script>
	import Header from '../lib/Header.svelte';
	import '../app.css';
</script>

<Header />

<main>
	<slot />
</main>

<style>
	main {
		background-color: white;
	}
</style>