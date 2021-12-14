<script>
    import Card from "./components/Card.svelte";
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
        href="https://fonts.googleapis.com/css2?family=Kumbh+Sans:wght@400;700&display=swap"
        rel="stylesheet"
    />
</svelte:head>
<div id="app">
    <div id="background-top">
        <img src="/assets/bg-pattern-top.svg" alt="Top Background Pattern" />
    </div>
    <div id="background-bottom">
        <img
            src="/assets/bg-pattern-bottom.svg"
            alt="Bottom Background Pattern"
        />
    </div>
    <div id="wrapper">
        <Card />
    </div>
</div>

<style>
    #app {
        position: fixed;
        background-color: rgb(24, 151, 164);
        height: 100vh;
        width: 100vw;
        z-index: -1;
    }
    #background-top > img {
        position: fixed;
        top: 0;
        left: 20%;
        transform: translate(-50%, -50%);
        z-index: -1;
    }
    #background-bottom > img {
        position: fixed;
        bottom: 0;
        right: 20%;
        transform: translate(50%, 50%);
        z-index: -1;
    }
    #wrapper {
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>
