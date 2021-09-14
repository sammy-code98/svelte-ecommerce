<script></script>

<main>
  <div class="container">
    <div class="text">Walk Shop Categories</div>
    <div class="items">
      <div class="sell-card">
        <img src="https://ng.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/80/953127/1.jpg?2370" alt="jum" class="sell-image">
        <p class="title">Men Sneakers</p>
        <p class="title">#5000</p>
      </div>
      <div class="sell-card">
        <img src="https://ng.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/72/245656/1.jpg?0874" alt="jum" class="sell-image">
        <p class="title">Andriod Phone</p>
        <p class="title">#52,000</p>
      </div>
      <div class="sell-card">
        <img src="https://ng.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/68/815536/1.jpg?9587" alt="jum" class="sell-image">
        <p class="title">Laptop Bag</p>
        <p class="title">#5400</p>
      </div>
      <div class="sell-card">
        <img src="https://ng.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/23/245656/1.jpg?7851" alt="jum" class="sell-image">
        <p class="title">Oppo Reno</p>
        <p class="title">#35000</p>
      </div>
      <div class="sell-card">
        <img src="https://ng.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/22/370822/1.jpg?5639" alt="jum" class="sell-image">
        <p class="title">Men Polo</p>
        <p class="title">#8000</p>
      </div>
      <div class="sell-card">
        <img src="https://ng.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/30/550396/1.jpg?8783" alt="jum" class="sell-image">
        <p class="title">Earpods</p>
        <p class="title">#5000</p>
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
      background-color: #FEE2CC;
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
    padding: 20px;
  }
  .sell-card{
    height: 100%;
    width: 200px;
    margin: 10px;
    border-radius: 8px;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
    cursor: pointer;
    transition: transform .2s;
  }
  .sell-image{
    width: 100%;
    border-top-right-radius: 8px;
    border-top-left-radius: 8px;
    
    
  }
  .title{
    font: 20px;
    margin-left: 12px;
  }
  .sell-card:hover{
    transform: scale(0.95); 
     }
</style>
