<script>
	import Search from "./Search.svelte"
</script>

<main>
    <nav class="nav">
		<span class="nav-log">Ecommerce</span>
		<Search class="search"/>
      <ul>
        <li><a href="#">Account</a></li>
        <li><a href="#">Cart</a></li>
        <li><a href="#">Help</a></li>
      </ul>
    </nav>
</main>

<style>
	
  .nav {
    display: flex;
	justify-content: space-between;
	align-self: center;
	background-color: #fff;
	box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px;
	width: 100%;
  }
  .nav-log{
	  font-size: 30px;
	  font-weight: 500;
	  color:#282828 ;
	  margin-left: 12px;
  }

  .nav ul {
    list-style-type: none;
    margin: 0;
	padding-top: 0;
    padding-left: 10px;
	float: right;
  }
  .nav ul li{
	  float: left;
  }
  .nav ul li a{
	  display: block;
	  text-decoration: none;
	  padding: 14px 16px;
	  color:#282828;
  }
  .nav ul li a:hover{
	  color: #f68b1e;;

  }
</style>


