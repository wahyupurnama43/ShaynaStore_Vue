<template>
  <div class="home">
    <HeaderShayna />
    <HeroHeader />
    <women-banner />
    <Instagram />
    <patner />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroHeader from "@/components/HeroHeader.vue";
import WomenBanner from "@/components/WomenBanner.vue";
import Instagram from "@/components/Instagram.vue";
import Patner from "@/components/Patner.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroHeader,
    WomenBanner,
    Instagram,
    Patner,
    FooterShayna,
  },
};
</script>
