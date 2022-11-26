<template>
  <header>
    <img src="@/img/dc-logo.png" alt="DC Logo">
    <ul>
      <li>CHARACTERS</li>
      <li>COMICS</li>
      <li>MOVIES</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>COLLECTIBLES</li>
      <li>VIDEOS</li>
      <li>FANS</li>
      <li>NEWS</li>
      <li>SHOP</li>
    </ul>
  </header>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  header {
    height: 10vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 10%;

    img {
      height: 80%;
      margin-right: 1rem;
    }

    ul{
      list-style: none;
      display: flex;
      gap: 1rem;
      height: 100%;
      align-items: center;

      li{
        font-weight: bold;
        display: flex;
        align-items: center;
        height: 100%;
        border-bottom: 5px solid transparent;
        color: black;
        cursor: pointer;

        &:hover{
          color: #0282f9;
          border-bottom: 5px solid #0282f9;
        }
      }
    }
  }
</style>
