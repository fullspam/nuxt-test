<template>
  <b-container>
    <b-navbar type="" variant=""  class="test">
      <b-navbar-brand href="#">
      <img src="https://placekitten.com/g/30/30" alt="Kitten">
      </b-navbar-brand>
      <b-navbar-nav>
        <b-nav-item class="pr-30" href="#">Our methodology</b-nav-item>
        <b-nav-item class="pl-30 pr-30" href="#">Services</b-nav-item>
        <b-nav-item class="pl-30 pr-30" href="#">Offices and teams</b-nav-item>
        <b-nav-item class="pl-30" href="#">Certifications and specializations</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
  </b-container>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name:'Nav',
  components: {

  }
})
</script>

<style lang="scss" scoped>
.nav-link {
    font-size: 20px;
    color: #7E7E7E;
    cursor: pointer;
    border-bottom: 1px solid #DADADA;
    font-weight: 300;
    position: relative;
    text-align: center;
    width: 100%;

    &:nth-child(2) {
      &::after {
        background: #4181F5;
      }
    }
    &:nth-child(3) {
      &::after {
        background: #4181F5;
      }
    }
    &:nth-child(4) {
      &::after {
        background: #4181F5;
      }
    }

    &::after {
      content: "";
      background: #4181F5;
      bottom: 0;
      height: 3px;
      left: 0;
      position: absolute;
      right: 0;
      transition: width 0.3s;
      width: 0;
    }

    &:hover,
    &.active {
      color: #4181F5;

      &:nth-child(2) {
        color: #4181F5;
      }
      &:nth-child(3) {
        color: #4181F5;
      }
      &:nth-child(4) {
        color: #4181F5;
      }
      &::after {
        width: 100%;
      }
    }

    &[disabled] {
      opacity: 0.5;
      cursor: auto;

      &:hover {
        color: #4181F5;
        &::after {
          width: 0;
        }
      }
    }
}
.pl-30 {
  padding-left: 30px;
}
.pr-30 {
  padding-right: 30px;
}
.test {
  margin-top: 50px;
  margin-bottom: 50px;
  justify-content: center;
  align-items: center;

}

.gf-tabs-items {
    
  }
</style>