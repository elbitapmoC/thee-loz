<script>
	import '../app.css';
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<div class="app">
	<Header />
	<main>
		<slot />
	</main>
	<Footer />
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		margin: 0 auto;
		padding: 3rem;
		box-sizing: border-box;
	}
</style>
