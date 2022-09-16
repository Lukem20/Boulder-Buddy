<script>
	import Banner from './components/Banner.svelte';

	let color = "blue";
	const toggle = () => {
		color = color === 'blue' ? 'red' : 'blue';
	}

</script>

<main>

	<Banner />
	
    <!-- <ProjectList {projects} /> -->

	<h1 style="color: {color}">Welcome!</h1>
	<button on:click={toggle} class="btn">Click me!</button>

</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	.btn {
		display: block;
		margin: 0 auto;
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