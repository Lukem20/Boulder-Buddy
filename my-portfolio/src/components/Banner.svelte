<script>
    import Logo from "./Logo.svelte";
    import Title from "./Title.svelte";
    import SearchBar from "./SearchBar.svelte";
</script>

<div class="container">
    <Logo />
    <img class="center-fit" src="assets/banner2.png" alt="Desert background graphic" />
    <div class="banner-intro">
        <Title />
        <SearchBar />
    </div>
</div>

<style>

    .banner-intro {
		color: aliceblue;
		/*text-transform: uppercase;*/
		font-size: 1.5em;
        position: relative;
        bottom: 8em;
    }
    
    .center-fit {
         max-width: 100%;
         object-fit:contain;
    }

</style>