<script>
   import Icon from 'svelte-awesome';
   import { search } from 'svelte-awesome/icons';

</script>

<main>
  <form action="#">
    <input type="text" placeholder="Search anythine here ....."/>
    <input type="submit" value="Search" />
  </form>
  <div class="mobile-search">
<Icon  data={search} scale="1.5" style="border: none; border-radius: 8px; padding: 2px; color:#f68b1e; margin-top:8px"/>
  </div>
</main>

<style>
    form{
        margin-top: 5px;
    }
    input[type=text]{
        border-radius: 8px;
        padding: 10px;

    }
    input[type=submit]{
        border: none;
        border-radius: 8px;
        background-color: #f68b1e;
        color: #fff;
        padding: 10px;
        margin-right: 12px;
    }
    input[type=text]:focus{
      outline: none;
    }
    .mobile-search{
      display: none;
    }
    @media only screen and (max-width: 668px) {
      form{
        display: none;
      }
      .mobile-search{
        display: block;
      }
    }
</style>
