<script>

</script>


<div id="rsvp">
  <h2>RSVP</h2>
  <div class="form">
    <form action="">
      <div class="form-control">
        <input type="text" id="name" placeholder="Name" required />
      </div>
      <div class="form-control">
        <input type="text" id="email-phone" placeholder="Email or Cell #" required />
      </div>
      <div class="form-control">
        <input type="number" id="num-guests" placeholder="Number of Guests (including you!)" required />
      </div>
      <div class="form-action">
        <button type="submit" class="btn">Submit</button>
      </div>
    </form>
  </div>
</div>


<style>
  h2 {
    text-align: center;
  }
  .form {
    background: white;
    border-radius: 3px;
    width: 100%;
    max-width: 375px;
    margin: auto;
    padding: 2rem 1rem;
  }
  .form-control {
    width: 100%;
    margin-bottom: 1rem;
  }
  .form-control input {
    width: 100%;
    border: none;
    border: 1px solid #333;
    border-radius: 3px;
    padding: 10px 5px;
    font-size: 1.2rem;
  }
</style>