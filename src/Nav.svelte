<script>
    import Search from "./Search.svelte"
</script>

<main>
  <nav class="navbar">
    <span class="nav-logo">Ecommerce</span>
    <Search />
    <ul class="nav-menu">
        <li class="nav-item">
            <a href="#" class="nav-link">Account</a>

        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Help</a>
            
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link">Cart</a>
            
        </li>
    </ul>
  </nav>
</main>

<style>
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #fff;
    padding:1rem;
    height: 20px;
    box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px;

  }
  .nav-logo {
    font-size: 30px;
    font-weight: 500;
    color: #f68b1e;
  }
  .nav-menu{
      display: flex;
      justify-content: space-between;
      align-items: center;
  }
  .nav-item{
      margin-left: 3rem;
      list-style: none;
  }
  .nav-link{
      font-size: 19px;
      color: #282828;
      text-decoration: none;
  }
  .nav-link:hover{
      color:#f68b1e;
  }
</style>
