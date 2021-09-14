<script></script>
<main>
    <div class="container">
        <div class="side-menu">
            <ul>
                <li>Supermarket</li>
                <li>Health & Beauty</li>
                <li>Home & Office</li>
                <li>Phones & Tablet</li>
                <li>Computing</li>
                <li>Electronics</li>
                <li>Fashion</li>
                <li>Gaming</li>
                <li>Automobile</li>

            </ul>

        </div>
        <div class="carousel">
            <img class="car-img" src="https://ng.jumia.is/cms/0-1-initiatives/spin-win/2021/spin-win_712x384.gif"  alt="imago">
  
        </div>
        <div>
            <div class="ad-card"> 
                <img class="ad-img" src="https://ng.jumia.is/cms/Homepage/2021/w32/blanks/899E0B86-BA02-4B04-AADF-16554FEA45A3.gif" alt="jjs">
            </div>
            <div class="ad-card">
            <img class="ad-img" src="https://ng.jumia.is/cms/Homepage/2021/w34/45447446-7AA5-4D23-B146-ECD7BF449CCA.gif" alt="dummy">
            </div>
        </div>
    </div>
</main>
<style>
    .container{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        row-gap: 10px;
        margin-top: 12px;
        width: 100%;
    }
    .side-menu{
        height: 400px;
        width: 200px;
        background-color: #fff;
        margin-left: 50px;
        box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
    }
    .side-menu ul li{
        cursor: pointer;
        text-decoration: none;
        list-style: none;
        font: 30px;
        margin-top: 10px;
        padding: 7px;
        color: #282828;
    }
    .side-menu ul li:hover{
        color: #f68b1e;
    }
    .carousel{
        width: auto;
        height: 400px;
        box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
        border-radius: 12px;
        margin-left: -12px;

        
    }
    .ad-card{
        border-radius: 12px;
        margin-bottom: 20px;
        margin-right: 55px;

    }
    .car-img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 12px;

    }
    .ad-img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 12px;
    }
</style>