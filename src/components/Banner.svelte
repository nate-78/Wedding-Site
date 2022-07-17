<script>
  import Image from "./controls/Image.svelte";
</script>

<div class="banner">
  <Image alt="couple kissing in a field"
    imgSrc="img/couple.jpg"
    imgType="image/jpeg" 
    webpSrc="img/couple.webp" 
    cssClass="cover"
  />
  <div class="headline">
    <h1>Lindsay + Nathan</h1>
  </div>
</div>

<style>
  .banner {
    width: 100%;
    max-width: 2800px;
    margin: auto;
    position: relative;
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
    top: 20%;
    color: black;
    font-size: 5rem;
  }
</style>