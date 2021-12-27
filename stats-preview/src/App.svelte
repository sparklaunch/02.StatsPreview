<script lang="ts">
    import Card from "./components/Card.svelte";
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
        href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Lexend+Deca&display=swap"
        rel="stylesheet"
    />
</svelte:head>
<main>
    <Card />
</main>

<style>
    main {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        min-height: 100vh;
        background-color: rgb(13, 14, 26);
    }
    @media screen and (max-width: 1440px) {
        main {
            background-color: black;
            position: relative;
            min-height: auto;
            height: auto;
            padding: 50px 0;
        }
    }
</style>
