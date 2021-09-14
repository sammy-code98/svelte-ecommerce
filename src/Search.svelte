<script></script>

<main>
  <form action="#">
    <input type="text" placeholder="Search anythine here ....."/>
    <input type="submit" value="Search" />
  </form>
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
    @media only screen and (max-width: 668px) {
      form{
        display: none;
      }
    }
</style>
