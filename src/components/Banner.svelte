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
</div>

<style>
  .banner {
    width: 100%;
    max-width: 2800px;
    margin: auto;
  }
</style>