<script></script>

<main>
  <div class="container">
    <div class="text">Walk Shop Categories</div>
    <div class="items">
      <div class="sell-card">
        <img
          src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/1-ws-mens-sneakers_260x144.png"
          alt="jum"
          class="sell-image"
        />
        <p class="title">Men's Sneakers</p>
      </div>
      <div class="sell-card">
        <img
          src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/2-ws-womens-sneakers_260x144.png"
          alt="jum"
          class="sell-image"
        />
        <p class="title">Women's Sneakers</p>

      </div>
      <div class="sell-card">
        <img
          src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/3-ws-kids-sneakers_260x144.png"
          alt="jum"
          class="sell-image"
        />
        <p class="title">Kid's Sneakers</p>

      </div>
      <div class="sell-card">
        <img
          src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/14-ws-womens-boots_260x144.png"
          alt="jum"
          class="sell-image"
        />
        <p class="title">Mens Sneakers</p>

      </div>
      <div class="sell-card">
        <img
          src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/4-ws-mens-slippers_260x144.png"
          alt="jum"
          class="sell-image"
        />
        <p class="title">Men's Slippers</p>

      </div>
      <div class="sell-card">
        <img
          src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/5-ws-women-sandals.png"
          alt="jum"
          class="sell-image"
        />
        <p class="title">Women's Sandals</p>

      </div>
    </div>
    <div class="items">
        <div class="sell-card">
          <img
            src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/6-ws-mens-formal-shoes_260x144.png"
            alt="jum"
            class="sell-image"
          />
          <p class="title">Men's Formal</p>

        </div>
        <div class="sell-card">
          <img
            src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/7-ws-womens-heels_260x144.png"
            alt="jum"
            class="sell-image"
          />
          <p class="title">Women's Heels</p>

        </div>

        <div class="sell-card">
          <img
            src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/11-ws-loafers_260x144.png"
            alt="jum"
            class="sell-image"
          />
          <p class="title">Men's Loafers</p>

        </div>
        <div class="sell-card">
          <img
            src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/12-ws-flats_260x144.png"
            alt="jum"
            class="sell-image"
          />
          <p class="title">Women's Flats</p>

        </div>
        <div class="sell-card">
          <img
            src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/13-ws-mens-boots_260x144.png"
            alt="jum"
            class="sell-image"
          />
          <p class="title">Men's Boots</p>

        </div>
        <div class="sell-card">
          <img
            src="https://ng.jumia.is/cms/0-1-weekly-cps/2021/w36/categories/walk-shop/14-ws-womens-boots_260x144.png"
            alt="jum"
            class="sell-image"
          />
          <p class="title">Women's Boots</p>

        </div>
      </div>
  </div>
</main>

<style>
  .container {
    width: 95%;
    height: auto;
    background-color: #fff;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
    margin: auto;
  }
  .text {
    background-color: #fee2cc;
    text-align: center;
    padding: 12px;
    font: 35px;
    font-weight: 500;
  }
  .items {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-right: 20px;
    padding: 10px;
  }
  .sell-card {
    height: 100%;
    width: 200px;
    margin: 10px;
    border-radius: 8px;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
    cursor: pointer;
    transition: transform 0.2s;
  }
  .sell-image {
    width: 100%;
    border-top-right-radius: 8px;
    border-top-left-radius: 8px;
  }
  .title {
    font: 10px;
    text-align: center;
  }
  .sell-card:hover {
    transform: scale(0.95);
  }
  @media only screen and (max-width: 768px) {
    .items{
      display: grid;
      grid-template-columns: repeat(3,1fr);
      gap: 10px;
      padding-bottom: 30px;

    }
    .sell-card{
      width: 85px;
      margin: 8px;

      
    }
  }
</style>
