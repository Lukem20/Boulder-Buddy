<script>
    import Logo from "./Logo.svelte"
    import SearchBar from "./SearchBar.svelte"
</script>

<div class="centerBox">
    <Logo />
    <img class="center-fit" src="assets/banner.png" alt="Desert background graphic" />
    <h1>Rock Buddy, an outdoor climbing guide.</h1>
    <SearchBar />

</div>

<style>

    h1 {
		color: aliceblue;
		/*text-transform: uppercase;*/
		font-size: 3em;
		font-weight: 100;
        position: relative;
        margin: 0 auto;
        bottom: 2em;
    }

    .centerBox {
            display: grid;
            height: 100%;
        }
        .center-fit {
            max-width: 100%;
            object-fit:contain;
        }

</style>