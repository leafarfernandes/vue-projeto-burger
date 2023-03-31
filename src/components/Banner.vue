<template>
  <div id="main-banner">
    <h1>Monte o seu hambúrguer</h1>
  </div>
</template>

<script>
export default {
  name: 'Banner'
}
</script>

<style scoped>

  #main-banner {
    background-image: url('/public/img/burger.jpg');
    background-position: 0 -250px;
    background-size: cover;
    display: flex;
    height: 500px;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 40px;
    background-color: #222;
    padding: 20px 40px;
  }

</style>