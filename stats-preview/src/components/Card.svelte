<script>
  import Left from "./Left.svelte";
  import Right from "./Right.svelte";
</script>

<div id="card">
  <Left />
  <Right />
</div>

<style>
  #card {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgb(26, 24, 49);
    border-radius: 15px;
    box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.5);
    display: flex;
    overflow: hidden;
    width: 800px;
  }
</style>
