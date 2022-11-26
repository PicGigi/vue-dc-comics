<template>
  <main>
    <div class="content-here">
      <h1>--> Content goes here &#60;--</h1>
    </div>
    <div class="blue-section">
      <div class="card">
        <img src="@/img/buy-comics-digital-comics.png" alt="">
        <span>DIGITAL COMICS</span>
      </div>
      <div class="card">
        <img src="@/img/buy-comics-merchandise.png" alt="">
        <span>DC MERCHANDISE</span>
      </div>
      <div class="card">
        <img src="@/img/buy-comics-subscriptions.png" alt="">
        <span>SUBSCRIPTION</span>
      </div>
      <div class="card">
        <img src="@/img/buy-comics-shop-locator.png" alt="">
        <span>COMIC SHOP LOCATOR</span>
      </div>
      <div class="card">
        <img src="@/img/buy-dc-power-visa.svg" alt="">
        <span>DC POWER VISA</span>
      </div>
    </div>
    <div class="big-section">
      <div class="list-section">
        <div class="list">
          <h2>DC COMICS</h2>
          <ul>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
          </ul>
        </div>
        <div class="list">
          <h2>SHOP</h2>
          <ul>
            <li>Text</li>
            <li>Text</li>
          </ul>
        </div>
        <div class="list">
          <h2>DC</h2>
          <ul>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
          </ul>
        </div>
        <div class="list">
          <h2>SITES</h2>
          <ul>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
            <li>Text</li>
          </ul>
        </div>
      </div>
      <img src="@/img/dc-logo-bg.png" alt="">
    </div>
  </main>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .content-here{
    background-color: black;
    height: 10vh;
    color: white;
    display: flex;
    align-items: center;
    padding: 0 10%;
    position: relative;
    z-index: 2;
  }

  .blue-section{
    background-color: #0282f9;
    height: 15vh;
    padding: 0 10%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
    position: relative;
    z-index: 2;
  }

  .card{
    height: 100%;
    display: flex;
    align-items: center;
    color: white;

    img{
      height: 40%;
      margin-right: 1rem;
    }
  }

  .big-section{
    height: 55vh;
    background-image: url("@/img/footer-bg.jpg");
    background-size: cover;
    padding: 2rem 10%;
    display: flex;
    z-index: 1;
    position: relative;
    .list-section{
      width: 50%;
      height: 100%;
      display: flex;
      flex-direction: column;
      flex-wrap: wrap;
      .list{
        max-width: fit-content;
        margin-right: 1rem;
      }

      h2{
        color: white;
        font-weight: bold;
        margin-top: 1rem;
      }

      ul{
        color: grey;
        list-style: none;
        font-size: 1.5rem;
      }
    }

    img{
      height: 150%;
      margin-left: 6rem;
      margin-top: -8rem;
    }
  }

</style>
