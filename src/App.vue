<script>
import AppTitle from './components/AppTitle.vue'
import JumboSection from './components/JumboSection.vue'

export default {
  name: 'myRoot',
  data: () => ({
    // possibili dati
  }),
  computed: {
    // possibili computed
  },
  methods: {
    // possibili metodi
  },
  components: {
    AppTitle,
    JumboSection
  }
  // eccetera
}
</script>

<template>
  <!-- Qui metto la struttura generale della pagina -->
  <div class="container">
    <AppTitle />
    <JumboSection />
  </div>
</template>

<style>
/* Qui metto lo stile generale */
body {
  background-color: gray;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
}

img {
  max-width: 100%;
}
</style>
