<script>
	import Banner from './components/Banner.svelte';
	import Leaderboard from './components/Leaderboard.svelte';
	import MtnSection from './components/MtnSection.svelte';

	let color = "blue";
	const toggle = () => {
		color = color === 'blue' ? 'red' : 'blue';
	}

</script>

<main>
	<Banner />
	<Leaderboard>
		<h2 style="color: {color}">Welcome!</h2>
		<button on:click={toggle} class="btn">Click me!</button>
	</Leaderboard>
	<MtnSection />

</main>

<style>
	main {
		max-width: none;
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
	
</style>