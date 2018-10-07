<template>
  <section>
    <h1 class="heading">{{ heading }}</h1>
  </section>
</template>

<script>
export default {
  data: function () {
    return {
      heading: "USERS!"
    }
  }
}
</script>

<style>
.heading {
  font-size: 20px;
  text-align: center;
  position: sticky;
  top: 0;
}
</style>
