<template>
  <div id="app" class="text-4xl text-green-700 text-center font-semibold">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Tailwind!"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
