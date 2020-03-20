<template>
  <b-container fluid="true" class="container">
    <b-row w-100>
      <b-col class="info">1 of 3</b-col>
      <b-col>2 of 3</b-col>
    </b-row>
  </b-container>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from './Logo.vue'

export default Vue.extend({
  name:'Header',
  components: {
    Logo
  }
})
</script>

<style>
.container{
  /* margin: 0 auto;
  min-height: 100vh;
  justify-content: center;
  align-items: center; */
  text-align: center;
}
.info {
  background-color: green;
  min-height: 100vh;
}
</style>

