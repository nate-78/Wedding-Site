<script>
  import Header from "../components/layout/Header.svelte";
  import Footer from "../components/layout/Footer.svelte";
  import Banner from "../components/Banner.svelte";
  import BannerGrid from "../components/BannerGrid.svelte";
  import Announce from "../components/Announce.svelte";
  import Details from "../components/Details.svelte";
  import Form from "../components/Form.svelte";
</script>

<svelte:head>
  <title>Lindsay & Nathan's Wedding</title>
</svelte:head>

<Header />

<BannerGrid />

<div>
  <div class="container">
    <div class="box outer">
      <div class="box inner">
        <Announce />
        <Details />
        <Form />
      </div>
    </div>
  </div>
</div>

<Footer />


<style>
  .box {
    border: 2px solid var(--font-color-dark);
    border-radius: 3px;
  }
  .box.outer {
    padding: 1rem;
    margin-bottom: 3rem;
  }
  .box.inner {
    padding: 4rem 1rem;
  }

  @media (max-width: 360px) {
    .box.outer {
      border: none;
      padding: none;
    }
  }
</style>