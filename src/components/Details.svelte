<script>

</script>


<hr />
<div class="col" id="when-and-where">
  <div>
    <h3>
      Saturday, the Third of September<br />
      Two Thousand Twenty-Two
    </h3>
    <span>
      at five o'clock in the evening
    </span>
  </div>
  <div>
    <h3 class="mt-2">
      EastWest 
      <span class="bullet">&bull;</span>
      <br class="mobile-break" /> 2306 2nd Ave N <br />
      Birmingham, AL 35203

    </h3>
  </div>
</div>
<hr />


<style>
  .col {
    align-items: center;
  }
  .col div * {
    text-align: center;
  }
  h3 {
    margin-bottom: 0.1rem;
  }
  span:not(.bullet) {
    font-style: italic;
    font-size: 1.5rem;
    display: flex;
    justify-content: center;
  }

  .mt-2 {
    margin-top: 2rem;
  }

  @media (max-width: 640px) {
    h3 {
      font-size: 16px;
      letter-spacing: 7px;
    }
    span:not(.bullet) {
      font-size: 1.1rem;
    }
  }

  @media (max-width: 500px) {
    h3 {
      letter-spacing: 3px;
    }
    .bullet {
      display: none;
    }
  }

  @media (min-width: 500px) {
    .mobile-break {
      display: none;
    }
  }
</style>