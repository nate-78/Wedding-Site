<div class="banner">
  <img src="img/us/morris-grainy.png" alt="" />
  <div class="headline">
    <h1>
      <div class="img">
        <img src="img/L&N2.png" alt="Lindsay + Nathan" />
      </div>
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
    margin-top: 3rem;
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
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .headline h1 .img {
    width: 300px;
    height: 300px;
    border-radius: 100%;
    border: 3px solid var(--white);
  }
  .headline h1 .img img {
    height: 100%;
    width: 100%;
    object-fit: contain;
    object-position: center;
    padding: 15px;
  }


  @media (max-width: 991px) {
    .headline h1 .img {
      width: 30vw;
      height: 30vw;
    }
  }
  @media (max-width: 430px) {
    .headline h1 .img {
      width: 130px;
      height: 130px;
    }
  }
</style>