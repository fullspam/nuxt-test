<template>
  <div>
    <Header />
    <Nav />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '~/components/Logo.vue'
import Header from '../components/Header.vue'
import Nav from '../components/Nav.vue'

export default Vue.extend({
  
  components: {
    Logo,
    Header,
    Nav
  }
})
</script>

<style>
</style>
