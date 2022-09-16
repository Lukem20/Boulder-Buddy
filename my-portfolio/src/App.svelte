<script>
	import Banner from './components/Banner.svelte';
	import Card from './components/Card.svelte'
	let color = "blue";
	const toggle = () => {
		color = color === 'blue' ? 'red' : 'blue';
	}

</script>

<main>

	<Banner />
	
    <!-- <ProjectList {projects} /> -->
	<Card>
		<h1 style="color: {color}">Welcome!</h1>
		<button on:click={toggle} class="btn">Click me!</button>
	</Card>
	

</main>

<style>
	main {
		text-align: center;
		margin: 0 auto;
		padding: 0 !important;
		background-color: #294936;
	}

	.btn {
		display: block;
		margin: 2rem auto;
		background: none;
		padding: 0.75em 1em;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

		main {
			max-width: none;
		}
	
</style>