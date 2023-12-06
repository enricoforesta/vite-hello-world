<script>
import AppTitleComponent from './components/AppTitleComponent.vue';
import AppHeroComponent from './components/AppHeroComponent.vue';

export default {
  data() {
    return {
      title: "VITE + VUE"
    }
  },
  components: {
    AppTitleComponent,
    AppHeroComponent
  }
}

</script>

<template>
  <header>
    <AppTitleComponent />
  </header>

  <main>
    <AppHeroComponent />
  </main>
</template>

<style scoped></style>
