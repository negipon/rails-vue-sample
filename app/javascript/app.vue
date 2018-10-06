<template>
  <div id="app">
    <p class="message">{{ message }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!"
    }
  }
}
</script>

<style scoped>
.message {
  font-size: 10vw;
  text-align: center;
}
</style>
