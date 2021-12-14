<script>
  import Card from "./components/Card.svelte";
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Lexend+Deca&display=swap"
    rel="stylesheet"
  />
</svelte:head>
<div id="app">
  <Card />
</div>

<style>
  #app {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgb(13, 14, 26);
  }
  @media screen and (max-width: 1440px) {
    #app {
      background-color: black;
    }
  }
</style>
