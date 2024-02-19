<script>
	import Header from './Header.svelte';
	import './styles.css';
	import '../app.css';
</script>

<div class="app flex flex-col min-h-screen justify-between">
	<Header />

	<main class="mb-auto">
		<slot />
	</main>

	<footer class="bg-gray-800 text-gray-300 p-5">
		<p class="text-center">Made with coffee</p>
	</footer>
</div>
