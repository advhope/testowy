<template>
  <div id="app">
    <AppNavbar />
    <main>
      <h1>Welcome to Your Vue Project</h1>
      <p>This is a simple example with a Navbar and Footer.</p>
    </main>
    <AppFooter />
  </div>
</template>

<script>
import AppNavbar from './components/AppNavbar.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    AppNavbar,
    AppFooter
  }
}
</script>

<style>
#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

main {
  flex: 1;
  padding: 1rem;
}
</style>
