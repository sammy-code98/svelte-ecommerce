<script></script>

<main>
  <div class="footer">
    <span class="nav-logo">Ecommerce</span>
    <div class="newsletter">
      <p class="text">New to Ecommerce ?</p>
      <span class="text2">Subscribe to our newsletter</span>
      <form action="#">
        <input type="email" placeholder="Enter E-mail Address" />
        <input type="submit" value="Male" />
        <input type="submit" value="Female" />
      </form>
    </div>
    <div>
        <p class="text">DOWNLOAD ECOMMERCE FREE APP</p>
        <span class="text2">Get access to exclusive offers</span>
        <br />
        <br />
        <button>App store</button>
        <button>Google play</button>
    </div>
  </div>
</main>

<style>
  .footer {
      width: 100%;
      
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    row-gap: 10px;
    height: auto;
    background-color: #323232;
  }
  .nav-logo {
    font-size: 30px;
    font-weight: 500;
    color: #f68b1e;
    margin-left: 30px;
    margin-top: 30px;
  }
  .text {
    color: #fff;
  }
  .text2 {
    color: #fff;
    font-size: 15px;
  }
  form{
      margin-top: 12px;
  }
  input[type="email"]{
      border: none;
      border-radius: 4px;
      padding: 10px;
  }
  input[type ="submit"]{
      border: none;
      border-radius: 4px;
      padding: 10px;
      margin: 4px;
      color: #f68b1e;
      cursor: pointer;
  }
  button{
      padding: 10px;
      border: none;
      border-radius: 4px;
      color: #f68b1e;
      cursor: pointer;
  }
</style>
