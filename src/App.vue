<template>
  <div>
    <header>
      <img src="./assets/img/logo.png" alt="Garbage Pail Kids" width="500">
      <h2>Your one stop shop for GPK cards!</h2>
    </header>
    <!-- Delete the section elements and add your components to this div -->
    <div>
      <section style="height: 300px; width: 200px; border: 1px solid black; margin: 0 auto;">
        <h1 style="text-align: center; margin-top: 125px;">Add your component here</h1>
      </section>
      <section  style="height: 150px; width: 600px; border: 1px solid black; margin: 24px auto;">
        <h1 style="text-align: center; margin-top: 50px;">Add your component here</h1>
      </section>
    </div>
    <footer>
      Carousel Project -- Jumbo Pail Corp -- © 1984 - 2019 © 
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