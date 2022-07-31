<script>
  import PayPalBtn from "./PayPalBtn.svelte";
</script>

<hr />
<div id="registry">
  <h2>Registry</h2>
  <p>
    Your presense at our wedding is the only gift we need! <br />
    However, for those who have expressed an interest, 
    it would mean the world to us if you contributed 
    to our honeymoon fund.
  </p>
  <div class="buttons">
    <a href="https://venmo.com/LindsaySmith8189" 
      target="_blank" class="btn"
    >
      Donate<br /> via Venmo
    </a>
    <a href="https://www.paypal.com/donate/?business=FEPMBACLR4L3A&no_recurring=1&item_name=Thank+you+so+much+for+helping+with+our+honeymoon%21&currency_code=USD"
      target="_blank" class="btn"
    >
      Donate<br /> via PayPal
    </a>
  </div>
</div>
<hr />

<style>
  h2 {
    text-align: center;
  }
  p {
    letter-spacing: 1px;
    font-style: italic;
    text-align: center;
    max-width: 500px;
    margin: 2rem auto;
    line-height: 1.5;
  }
  .buttons {
    display: flex;
    justify-content: center;
    align-items: center;
    grid-gap: 2rem;
  }
  .buttons > a {
    margin: 0;
    text-align: center;
    font-size: 14px;
    letter-spacing: 7px;
    padding: 8px 25px;
    justify-content: center;
    align-items: center;
  }

  @media (max-width: 630px) {
    .buttons {
      flex-direction: column;
    }
  }
</style>