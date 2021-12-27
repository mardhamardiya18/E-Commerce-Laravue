<template>
  <div class="home">
    <Navbar />
    <HeroSection />
    <ProductSection />
    <SosmedSection />
    <PartnerSection />
    <FooterSection />
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    Navbar: () => import("@/components/NavbarComponent.vue"),
    HeroSection: () => import("@/components/HeroComponent"),
    ProductSection: () => import("@/components/ProductComponent"),
    SosmedSection: () => import("@/components/SosMedComponent"),
    PartnerSection: () => import("@/components/PartnerComponent"),
    FooterSection: () => import("@/components/FooterComponent"),
  },
};
</script>

<style scoped>
</style>
