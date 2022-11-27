<template>
  <main>
    <div class="content-here">
      <div class="copertina" />
      <div class="card-section">
        <CardPage
          v-for="objCard in arrCards"
          :key="objCard.series"
          class="card-main"
          :card-img="objCard.thumb"
          :card-title="objCard.series"
        />
      </div>
    </div>
    <div class="blue-section">
      <div class="card">
        <img
          src="@/img/buy-comics-digital-comics.png"
          alt=""
        >
        <span>DIGITAL COMICS</span>
      </div>
      <div class="card">
        <img
          src="@/img/buy-comics-merchandise.png"
          alt=""
        >
        <span>DC MERCHANDISE</span>
      </div>
      <div class="card">
        <img
          src="@/img/buy-comics-subscriptions.png"
          alt=""
        >
        <span>SUBSCRIPTION</span>
      </div>
      <div class="card">
        <img
          src="@/img/buy-comics-shop-locator.png"
          alt=""
        >
        <span>COMIC SHOP LOCATOR</span>
      </div>
      <div class="card">
        <img
          src="@/img/buy-dc-power-visa.svg"
          alt=""
        >
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
      <img
        src="@/img/dc-logo-bg.png"
        alt=""
      >
    </div>
  </main>
</template>

<script>
import CardPage from '@/components/CardPage.vue';

export default {
  name: 'MainPage',
  components: {
    CardPage,
  },
  data() {
    return {
      arrCards: [
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX',
          price: '$19.99',
          series: 'Action Comics',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01',
          price: '$3.99',
          series: 'American Vampire 1976',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb',
          price: '$16.99',
          series: 'Aquaman',
          type: 'graphic novel',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76',
          price: '$2.99',
          series: 'Batgirl',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
          price: '$3.99',
          series: 'Batman',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
          price: '$2.99',
          series: 'Batman Beyond',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8',
          price: '$3.99',
          series: 'Batman/Superman',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk',
          price: '$4.99',
          series: 'Batman/Superman Annual',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8',
          price: '$5.99',
          series: 'Batman: The Joker War Zone',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY',
          price: '$6.99',
          series: 'Batman: Three Jokers',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX',
          price: '$4.99',
          series: 'Batman: White Knight Presents: Harley Quinn',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq',
          price: '$16.99',
          series: 'Catwoman',
          type: 'graphic novel',
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>

  .copertina{
    background-image: url("@/img/jumbotron.jpg");
    background-size: cover;
    height: 50vh;
  }

  .card-section{
    background-color: black;
    padding: 2rem 10%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;

    .card-main {
      flex: 0 0 16.6666666667%;
    }
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
