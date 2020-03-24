<template>
  <b-container fluid class="our-container">
    <b-container class="our-methodology">
      <b-row>
        <b-col cols="12" lg="6" class="our-image">
          <b-img class="image" src="~assets/image/our-methodology.png" fluid alt="Responsive image"></b-img>
        </b-col>
        <b-col cols="12" lg="6" class="our-info">
          <div>
            <p class="our-title">Our <br class="line-break">methodology</p>
            <p class="our-text">We develop and implement <span class="blue-text">digital <br>strategies</span> with an analytical background.</p>
          </div>
          <b-row>
            <b-col cols="12" md="6">
              <div class="d-flex attributes">
                <img src="~assets/icon/trending_up-24px.svg" class="our-icon" alt="">
                <p class="our-paragraph">We develop and apply technologies that optimizes business results.</p>
              </div>
            </b-col>
            <b-col cols="12" md="6">
              <div class="d-flex attributes">
                <img src="~assets/icon/perm_phone_msg-24px.svg" class="our-icon" alt="">
                <p class="our-paragraph">We use a dedicated Support Center for an optimal customer service.</p>
              </div>
            </b-col>
            <b-col cols="12" md="6">
              <div class="d-flex attributes">
                <img src="~assets/icon/person-24px.svg" class="our-icon" alt="">
                <p class="our-paragraph">Specialized teams and data-based digital methodologies.</p>
              </div>
            </b-col>
            <b-col cols="12" md="6">
              <div class="d-flex attributes">
                <img src="~assets/icon/library_add_check-24px.svg" class="our-icon" alt="">
                <p class="our-paragraph">Optimization and automation of processes to scale up campaigns.</p>
              </div>
            </b-col>
          </b-row>
          <!-- <b-row>
            <b-col>
              <div class="d-flex">
                <img src="~assets/icon/person-24px.svg" class="our-icon" alt="">
                <p class="our-paragraph">Specialized teams and data-based digital methodologies.</p>
              </div>
            </b-col>
            <b-col>
              <div class="d-flex">
                <img src="~assets/icon/library_add_check-24px.svg" class="our-icon" alt="">
                <p class="our-paragraph">Optimization and automation of processes to scale up campaigns.</p>
              </div>
            </b-col>
          </b-row> -->
        </b-col>
      </b-row>
    </b-container>
    <!-- <div class="supported">
      <p class="support-title">We are endorsed and supported<br>as an industry leader</p>
      <b-container>    
        <b-row>
          <b-col cols="2"><img src="~assets/image/support-gp.png" alt=""></b-col>
          <b-col cols="2"><img src="~assets/image/support-gc.png" alt=""></b-col>
          <b-col cols="2"><img src="~assets/image/support-waze.png" alt=""></b-col>
          <b-col cols="2"><img src="~assets/image/support-fb.png" alt=""></b-col>
          <b-col cols="2"><img src="~assets/image/support-ia.png" alt=""></b-col>
          <b-col cols="2"><img src="~assets/image/support-pipe.png" alt=""></b-col>
        </b-row>
      </b-container>
      <p class="support-subtitle"><span class="text-color">Our teams work</span> and learn with worldwide experts in technology</p>
    </div> -->
  </b-container>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '../components/Logo.vue'

export default Vue.extend({
  name:'OurMethodology',
  components: {
    Logo
  }
})
</script>

<style lang="scss" scoped>
.our-container {
  padding: 0px;
  text-align: center;
  .our-methodology {
    padding-bottom: 70px;
    .our-image {
      align-self: center;
      .image {
        justify-content: center;
        align-self: center;
      }
    }
    .our-info {
      // margin-left: 15px;
      .our-title {
        color: #454545;
        font-size: 60px;
        font-weight: 700;
        line-height: 70px;
        text-align: left;
        @media (max-width: 992px) { 
          text-align: center;
        }
        @media (max-width: 768px) { 
          font-size: 30px;
        }
        .line-break {
          display: block;
          @media (max-width: 992px) { 
            display: none;
          }
        }
      }
      .our-text {
        color: #7E7E7E;
        font-size: 25px;
        line-height: 35px;
        .blue-text {
          color: #4181F5;
        }
        @media (max-width: 768px) { 
          font-size: 16px;
          line-height: 22px;
        }
      }
      .our-icon {
        color: #7E7E7E;
        align-self: flex-start;
        padding-right: 15px;
      }
      .attributes {
        @media (max-width: 768px) { 
        padding: 0 20px; 
        }
      }
      .our-paragraph {
        color: #454545;
        font-size: 16px;
        line-height: 26px;
        font-weight: 400;
        text-align: left;
        @media (max-width: 768px) { 
          font-size: 14px;
          line-height: 20px;
          margin: 0px 20x;
        }
      }
    }
  }
  .supported {
    background-color: #F8F9FA;
    padding: 80px 0px;
    .support-title {
      padding-bottom: 33px;
      font-size: 40px;
      font-weight: 700;
      line-height: 50px;
      color: #454545;
    }
    .support-subtitle {
      padding-top: 65px;
      color: #7E7E7E;
      font-size: 25px;
      line-height: 35px;
      .text-color {
        color: #4181F5;
      }
    }
  }
}
</style>