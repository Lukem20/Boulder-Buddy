<script>
    import Logo from "./Logo.svelte"
    import SearchBar from "./SearchBar.svelte"
</script>

<div class="container">
    <Logo />
    <img class="center-fit" src="assets/banner.png" alt="Desert background graphic" />
    <div class="banner-intro">
        <h1>Rock Buddy, an outdoor climbing guide.</h1>
        <SearchBar />
    </div>
</div>

<style>

    .banner-intro {
		color: aliceblue;
		/*text-transform: uppercase;*/
		font-size: 1.5em;
        position: relative;
        bottom: 6em;
    }

    .center-fit {
         max-width: 100%;
         object-fit:contain;
    }

</style>