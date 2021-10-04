<template>
  <Header/>

  <destination/>
</template>

<script>
import Header from './components/Header.vue'
import Destination from './components/Destination.vue'
export default {
  name: 'App',
  components: {
    Header,
    Destination
  }
}
</script>

<style>
@import url(assets/scss/normalize.scss);
</style>
