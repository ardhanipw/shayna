<template>
  <div class="home">
    
    <HeaderShayna />
    <HeroShayna />
    <ProductSliderShayna />
    <SocialMediaShayna />
    <PartnerShayna />
    <FooterShayna />
    
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import ProductSliderShayna from '@/components/ProductSliderShayna.vue'
import SocialMediaShayna from '@/components/SocialMediaShayna.vue'
import PartnerShayna from '@/components/PartnerShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'


export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    ProductSliderShayna,
    SocialMediaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
