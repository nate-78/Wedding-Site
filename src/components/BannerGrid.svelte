<script>
  import Image from "./controls/Image.svelte";
</script>

<div class="banner">
  <div class="grid">
    <div>
      <img src="img/us/barons.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/bourbon-street.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/concert.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/kessel-run.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/legion.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/engaged.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/engaged-carrigans.webp" alt="" />
    </div>
    <div>
      <img src="img/us/new-orleans.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/paper-doll.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/restaurant.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/vulcan.jpg" alt="" />
    </div>
    <div>
      <img src="img/us/siluria.jpg" alt="" />
    </div>
  </div>
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

  .grid {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(6, 1fr);
  }
  .grid > div > img {
    object-fit: cover;
    width: 100%;
    height: 100%;
  }
</style>