<template>
  <!-- Partner Logo Section Begin -->
  <div class="partner-logo">
    <div class="container">
      <carousel class="logo-carousel" :dots="false" :item="5" :loop="true" :autoplay="true" :nav="false" :margin="0">
        <div class="logo-item">
          <div class="tablecell-inner">
              <img src="../../public/img/logo-carousel/logo-1.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
              <img src="../../public/img/logo-carousel/logo-2.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
              <img src="../../public/img/logo-carousel/logo-3.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
              <img src="../../public/img/logo-carousel/logo-4.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
              <img src="../../public/img/logo-carousel/logo-5.png" alt="" />
          </div>
        </div>
      </carousel>
    </div>
  </div>
  <!-- Partner Logo Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel'

export default {
  name: 'PartnerShayna',
  components: {
    carousel
  }
  
}
</script>

