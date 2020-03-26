<template>
  <b-container fluid class="">
    <b-row>
      <b-col cols="12" lg="6" class="info">
        text
      </b-col>
      <b-col cols="12" lg="6" class="image">
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
  height: 100vh;
  @media (max-width: 992px) { 
    height: 70vh;
  }
}
.image {
  padding: 0;
  .img {
    height: 100vh;
    width: 100%;
    @media (max-width: 992px) { 
      height: 30vh;
    }
  }
}
</style>

