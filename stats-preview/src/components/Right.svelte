<script>
  $: innerWidth = 0;
</script>

<svelte:window bind:innerWidth />
<div id="right">
  <img
    src={innerWidth > 1440
      ? "/assets/image-header-desktop.jpg"
      : "/assets/image-header-mobile.jpg"}
    alt="Header"
  />
</div>

<style>
  #right {
    width: 50%;
  }
  #right > img {
    height: 100%;
    filter: sepia(100%) hue-rotate(230deg) saturate(500%) brightness(0.75);
  }
  @media screen and (max-width: 1440px) {
    #right {
      width: 100%;
      border-top-left-radius: 15px;
      border-top-right-radius: 15px;
      overflow: hidden;
    }
    #right > img {
      height: auto;
      width: 100%;
    }
  }
</style>
