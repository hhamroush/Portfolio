<script>
	import Nav from '../components/nav.svelte';
	import '../app.scss'; 
</script>

<div>
	<nav />

	<main>
		<slot />
	</main>

	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>
</div>

