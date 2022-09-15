<script>
    import Logo from "./Logo.svelte"
</script>

<div class="bannerBox">
    <Logo />
    <img class="center-fit" src="assets/banner.png" alt="Desert background graphic" />
</div>

<style>

    .bannerBox {
            display: grid;
            height: 100%;
        }
        .center-fit {
            max-width: 100%;
            max-height: 100vh;
            margin: auto;
        }

</style>