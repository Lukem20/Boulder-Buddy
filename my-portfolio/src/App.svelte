<script>
	import ProjectList from './components/ProjectList.svelte';
	import Banner from './components/Banner.svelte';

	let firstName = 'Luke';
	let lastName = 'Moore';
	let color = "blue";

	$: name = firstName + ' ' + lastName;

	const toggle = () => {
		color = color === 'blue' ? 'red' : 'blue';
	}

	const projects = [
		{
			id: 1,
			desc: "Example description 1."
		},
		{
			id: 2,
			desc: "Example description 2."
		},
		{
			id: 3,
			desc: "Example description 3."
		},
	];

</script>

<main>

	<Banner />
	
	<ProjectList {projects} />

	<h1 style="color: {color}">Hello {name}!</h1>
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

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>