<script setup>
import Sport from './components/Sport.vue'
</script>

<template class="app">
  <header>
    <img alt="logo" class="logo" src="./assets/logo.jpg" width="75%" height="50%" />
  </header>

  <main>
    <Sport/>
  </main>
</template>

<style scoped>
.app {
  justify-content: center;
  justify-items: center;
  height: 100vh;
  background-color: pink;
  margin: 20% auto;
}

.logo {
  justify-items: center;
  margin: 20% auto;
}

main {
  color:white;
  display: grid;
  margin: 10% auto;
}
</style>
