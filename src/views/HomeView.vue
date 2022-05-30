<template>
  <div class="home">
      <!-- Header Section Begin -->
      <HeaderShayna  />
      <!-- Header End -->

    <!-- Hero Section Begin -->
    <SliderSection />
    <!-- Hero Section End -->

    <!-- Woman Banner Section Begin -->
    <WomanBannerSection />
    <!-- Woman Banner Section End -->

    <InstaSection />

    <PartnerLogoSection />

    <FooterShayna />

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';
import SliderSection from '@/components/SliderSection.vue';
import WomanBannerSection from '@/components/WomanBannerSection.vue';
import InstaSection from '@/components/InstaSection.vue';
import PartnerLogoSection from '@/components/PartnerLogoSection.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
    name: 'HomeView',
    components: {
    HeaderShayna,
    SliderSection,
    WomanBannerSection,
    InstaSection,
    PartnerLogoSection,
    FooterShayna
}
}
</script>
