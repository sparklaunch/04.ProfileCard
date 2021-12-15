<script>
    import Banner from "./Banner.svelte";
    import Profile from "./Profile.svelte";
    import Info from "./Info.svelte";
</script>

<div id="card">
    <Banner />
    <Profile />
    <Info />
</div>

<style>
    #card {
        border-radius: 10px;
        box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.25);
        background-color: white;
        width: 400px;
        overflow: hidden;
    }
</style>
