<template>
  <div class="home">
  <ShaynaHeader/>
   <HeroSection/>
   <WomenShayna/>
   <InstaShayna/>
   <PartnerShayna/>
   <FooterShayna/>
  </div>
</template>

<script>
import ShaynaHeader from "@/components/ShaynaHeader.vue";
import HeroSection from "@/components/HeroSection.vue";
import WomenShayna from "@/components/WomenShayna.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerShayna from "@/components/PartnerShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";
// import carousel from 'vue-owl-carousel';



export default {
  name: 'home',
  components:{
      ShaynaHeader,
      HeroSection,
      WomenShayna,
      InstaShayna,
      PartnerShayna,
      FooterShayna
    //   carousel
      
  }
};
</script>

