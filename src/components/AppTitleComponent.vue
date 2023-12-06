<script>
export default {
  name: "Titolo header",
  data() {
    return {
      title: "La mia prima App con VITE"
    }
  }
}
</script>

<template>
  <h2>{{ title }}</h2>
</template>

<style scoped>
h2 {
  color: yellow;
  text-align: center;
}
</style>
