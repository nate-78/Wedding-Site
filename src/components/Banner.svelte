<script>
  import Image from "./controls/Image.svelte";
</script>

<div class="banner">
  <img src="img/us/morris-grainy.png" alt="" />
  <div class="headline">
    <h1>
      <img src="img/L&N2.png" alt="Lindsay + Nathan" />
    </h1>
  </div>
</div>

<style>
  .banner {
    width: 100%;
    max-width: 2800px;
    margin: auto;
    position: relative;
    margin-bottom: 3rem;
  }
  .banner > img {
    width: 100%;
  }
  .headline {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
  }
  .headline h1 {
    position: relative;
    color: black;
    font-size: 5rem;
  }
  .headline h1 img {
    width: 570px;
  }
</style>