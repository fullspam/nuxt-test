<template>
  <b-container fluid class="">
    <b-row>
      <b-col class="info">
        text
      </b-col>
      <b-col class="image">
        <b-img class="img" src="~assets/image/img-1.jpg" fluid alt="Responsive image"></b-img>
      </b-col>
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

<style lang="scss">
.container{
  /* margin: 0 auto;
  min-height: 100vh;
  justify-content: center;
  align-items: center; */
  text-align: center;
}
.info {
  background-color: #4181F5;
  min-height: 100vh;
}
.image {
  padding: 0;
  .img {
    height: 100vh;
    width: 100%;
  }
}
</style>

