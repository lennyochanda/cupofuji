<script>
	import Hero from './components/Hero.svelte'
</script>

<main>
</main>
<Hero />


<style>
	main {
		text-align: center;
		padding: 0;
		margin: 0;
		width: 100%;
		height: 100%;
		background-image: linear-gradient(rgba(0, 110, 0, 0.7), rgba(0, 0, 150, 0.6)), url("/images/hero.jpg");
		background-repeat: no-repeat;
		background-size: cover;
		filter:  grayscale(40%);
	}
</style>