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
    <div class="hamburger">
      <span class="bar" />
      <span class="bar" />
      <span class="bar" />
    </div>
  </nav>
</main>

<style>
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #fff;
    padding: 1rem;
    height: 20px;
    box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px;
    position: fixed;
    width: 95vw;
    top: 0;
  }
  .nav-logo {
    font-size: 30px;
    font-weight: 500;
    color: #f68b1e;
  }
  .nav-menu {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .nav-item {
    margin-left: 3rem;
    list-style: none;
  }
  .nav-link {
    font-size: 19px;
    color: #282828;
    text-decoration: none;
  }
  .nav-link:hover {
    color: #f68b1e;
  }
  .hamburger {
    display: none;
  }

  .bar {
    display: block;
    width: 25px;
    height: 3px;
    margin: 5px auto;
    transition: all 0.3s ease-in-out;
    background-color: #f68b1e;
  }
  /* media queries */
  @media only screen and (max-width: 768px) {
    .navbar {
      width: 340px;
    }
    .nav-logo {
      font-size: 30px;
    }
    .nav-menu {
      position: fixed;
      left: -100%;
      top: 5rem;
      flex-direction: column;
      width: 300px;
      background-color: #fff;
      border-radius: 10px;
      text-align: center;
      transition: 0.3s;
      box-shadow: 0 10px 27px rgba(0, 0, 0, 0.05);
    }
    .nav-item {
      margin: 2.5rem 0;
    }
    .hamburger {
      display: block;
      cursor: pointer;
    }
    .hamburger.active .bar:nth-child(2) {
      opacity: 0;
    }

    .hamburger.active .bar:nth-child(1) {
      transform: translateY(8px) rotate(45deg);
    }

    .hamburger.active .bar:nth-child(3) {
      transform: translateY(-8px) rotate(-45deg);
    }
  }
</style>

<script>
  import Search from "./Search.svelte";
  let hamburger = document.querySelector(".hamburger");
  let navMenu = document.querySelector(".nav-menu");
  let navLink = document.querySelectorAll(".nav-link");

// hamburger.addEventListener("click", mobileMenu); 
  function mobileMenu() {
    hamburger.classList.toggle("active");
    navMenu.classList.toggle("active");
  }

  navLink.forEach((n) => n.addEventListener("click", closeMenu));

  function closeMenu() {
    hamburger.classList.remove("active");
    navMenu.classList.remove("active");
  }
</script>
