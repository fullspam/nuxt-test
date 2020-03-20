<template>
  <b-container fluid class="container">
    <Header />
  </b-container>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '~/components/Logo.vue'
import Header from '../components/Header.vue'

export default Vue.extend({
  components: {
    Logo,
    Header
  }
})
</script>

<style>

</style>
