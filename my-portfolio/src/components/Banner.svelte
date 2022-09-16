<script>
    import Logo from "./Logo.svelte"
</script>

<div class="centerBox">
    <Logo />
    <img class="center-fit" src="assets/banner.png" alt="Desert background graphic" />
    <h1>Rock Buddy, an outdoor climbing guide.</h1>
</div>

<style>

    h1 {
		color: aliceblue;
		/*text-transform: uppercase;*/
		font-size: 3em;
		font-weight: 100;
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