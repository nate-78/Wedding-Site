<script>
  export let alt;
  export let webpSrc;
  export let imgSrc;
  export let imgType;
  export let cssClass;

  import { createEventDispatcher } from 'svelte';

	const dispatch = createEventDispatcher();

  function clickEvent() {
    dispatch('click');
  }
</script>

<picture on:click={clickEvent} class={cssClass}>
  <source srcset={webpSrc} type="image/webp">
  <source srcset={imgSrc} type={imgType}> 
  <img src={imgSrc} alt={alt}>
</picture>

<style>
  .cover img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
</style>