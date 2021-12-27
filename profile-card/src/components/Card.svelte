<script lang="ts">
    import Banner from "./Banner.svelte";
    import Profile from "./Profile.svelte";
    import Info from "./Info.svelte";
    import Details from "./Details.svelte";
</script>

<div id="card">
    <Banner />
    <Profile />
    <Info />
    <hr />
    <Details />
</div>

<style>
    #card {
        border-radius: 10px;
        box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.25);
        background-color: white;
        width: 400px;
        overflow: hidden;
    }
    hr {
        border-color: rgb(227, 227, 227);
        border-style: solid;
    }
    @media all and (max-width: 1440px) {
        #card {
            width: 90%;
        }
    }
</style>
