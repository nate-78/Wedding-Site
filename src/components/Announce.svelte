<script>

</script>

<div class="top row">
  <div class="col left">
    <span>Lindsay</span>
    <span>Ann</span>
    <span>Smith</span>
  </div>
  <div class="col">
    <!-- <div class="huge">
      &amp;
    </div> -->
    <img src="img/And2.png" alt="and" />
  </div>
  <div class="col right">
    <span>James</span>
    <span>Nathan</span>
    <span>Owens</span>
  </div>
</div>


<style>
  .row {
    justify-content: center;
  }
  .col {
    margin: 0 1rem;
    text-align: center;
  }
  .col span {
    font-size: 1.7rem;
    text-transform: uppercase;
    letter-spacing: 21px;
    font-family: var(--font-headings);
  }
  /* .col.left {
    text-align: right;
  }
  .col.right {
    text-align: left;
  } */
  /* .huge {
    font-size: 7rem;
    line-height: 1;
    position: relative;
    top: -4px;
  } */
  img {
    width: 150px;
    position: relative;
    top: 30px;
  }

  @media (max-width: 991px) {
    .row {
      flex-direction: column;
    }
    .col span {
      font-size: 1.3rem;
    }
    img {
      width: 67px;
      top: 0;
      margin: 1rem auto;
    }
  }
  @media (max-width: 550px) {
    .col span {
      font-size: 1rem;
      letter-spacing: 15px;
    }
  }
</style>