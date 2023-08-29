<script setup>
import Header from './components/header/header.vue'
import HeaderHero from './components/hero/HeaderHero.vue'
import FeatureHero from './components/hero/FeatureHero.vue';
import FeaturesHero from './components/hero/FeaturesHeroTwo.vue'
import HowItWorksHero from './components/hero/HowItWorksHero.vue'
import CallToAction from './components/section/CallToAction.vue'
import Newsletter from './components/section/Newsletter.vue'
import Footer from './components/footer/Footer.vue'
</script>

<template>
  <section class="overflow-hidden" style="background: url(https://shuffle.dev/gradia-assets/images/hero/bg.png) no-repeat; background-size: cover;">
    <Header />
    <HeaderHero />
  </section>
    <FeatureHero />
    <FeaturesHero />
    <HowItWorksHero />
    <CallToAction />
    <Newsletter />
    <Footer />
</template>

