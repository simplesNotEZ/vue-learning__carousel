<template>
  <div>
    <header>
      <img src="./assets/img/logo.png" alt="Garbage Pail Kids" width="500">
      <h2>Your one stop shop for GPK cards!</h2>
    </header>
    <h1 style="text-align: center; margin-top: 125px;">Add your component here</h1>
    <footer>
      Carousel Project -- Jumbo Pail Corp -- © 1984 - 2020 © 
    </footer>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style scoped>
  header {
    text-align: center;
  }

  header img {
    margin: 24px 0;
  }

  footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    text-align: center;
    padding: 16px;
    color: #999;
    font-size: 14px;
  }
</style>