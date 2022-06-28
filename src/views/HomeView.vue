<template>
  <div class="home">
    <HeaderShaynaVue />
    <HeroShaynaVue />
    <BannerShayna />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShaynaVue from '@/components/HeaderShayna.vue'
import HeroShaynaVue from '@/components/HeroShayna.vue'
import BannerShayna from '@/components/BannerShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PartnerShayna from '@/components/PartnerShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'



export default {
  name: 'HomeView',
  components: {
    HeaderShaynaVue,
    HeroShaynaVue,
    BannerShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
}
}
</script>
