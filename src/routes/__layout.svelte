<svelte:head>
	<link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,300;0,400;0,600;0,700;1,200;1,300;1,400;1,600;1,700&display=swap" rel="stylesheet">
	<meta name="robots" content="noindex nofollow" />
	<html lang="en" />
</svelte:head>

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
		padding-top: 50px;
	}
</style>