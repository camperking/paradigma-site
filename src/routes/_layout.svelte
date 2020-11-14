<script>
	import Footer from '../components/Footer.svelte';
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<style>
	main {
		position: relative;
		max-width: 60vw;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
		text-align: center;
	}

	@media (max-width: 1650px) {
		main {
			max-width: 80vw;
		}
	}

	@media (max-width: 850px) {
		main {
			max-width: 100vw;
		}
	}
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>

<Footer />
