<script>
    import Logo from "./Logo.svelte"
</script>

<div class="centerBox">
    <Logo />
    <img class="center-fit" src="assets/banner.png" alt="Desert background graphic" />
</div>

<style>
    .centerBox {
            display: grid;
            height: 100%;
        }
        .center-fit {
            max-width: 100%;
            object-fit:contain;
        }

</style>