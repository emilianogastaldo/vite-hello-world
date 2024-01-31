<script>
import ViteHello from './components/ViteHello.vue'

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
    ViteHello
  }
  // eccetera
}
</script>

<template>
  <!-- Qui metto la struttura generale della pagina -->
  <div class="container">

    <ViteHello />
  </div>
</template>

<style>
/* Qui metto lo stile generale */
body {
  background-color: aliceblue;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
}
</style>
