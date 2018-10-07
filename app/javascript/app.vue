<template lang="pug">
  #app
    p.message {{ message }}
</template>

<script>
export default {
  data: function () {
    return {
      message: "HOME"
    }
  }
}
</script>

<style>
.message {
  font-size: 10vw;
  text-align: center;
}
</style>
