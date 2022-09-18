<script>
	import Banner from './components/Banner.svelte';
	import FeaturedList from './components/FeaturedList.svelte';
	import Leaderboard from './components/Leaderboard.svelte';
	import MtnSection from './components/MtnSection.svelte';

</script>

<main>

	<Banner />
	<FeaturedList />
	<Leaderboard />
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
	
</style>