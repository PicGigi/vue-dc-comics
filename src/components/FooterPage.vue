<template>
  <footer>
    <button>SIGN-UP NOW!</button>
    <div class="follow-section">
      <span>FOLLOW US</span>
      <img src="@/img/footer-facebook.png" alt="">
      <img src="@/img/footer-twitter.png" alt="">
      <img src="@/img/footer-youtube.png" alt="">
      <img src="@/img/footer-pinterest.png" alt="">
      <img src="@/img/footer-periscope.png" alt="">
    </div>
  </footer>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  footer{
    background-color: #383434;
    height: 10vh;
    position: relative;
    z-index: 2;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 10%;

    button{
      background-color: transparent;
      border: 3px solid #0282f9;
      color: white;
      padding: .5rem;
    }

    .follow-section{
      display: flex;
      align-items: center;
      gap: 1rem;
      color: #0282f9;
      font-weight: bold;
    }
  }
</style>
