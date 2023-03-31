<template>
  <div class="message-container">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name:'Message',
  props: {
    msg: String
  }
}
</script>

<style scoped>

  .message-container {
    color: #0861c0;
    background-color: #84bcf8;
    border: 2px solid #9bc0e7;
    border-radius: 5px;
    padding: 10px;
    max-width: 400px;
    margin: 30px auto;
  }


</style>