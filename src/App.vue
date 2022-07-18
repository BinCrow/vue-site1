<template>
  <HeaderSection />
  <SliderSection />
  <ImageSection skill="section" />
  <ImgTextSection skill="section" />
  <CardSection skill="section" />
  <BannerSection skill="section banner__wrap" />
  <TextSection skill="section" />
  <FooterSection skill="section" />
</template>

<script>
 import HeaderSection from './components/HeaderSection.vue'
 import SliderSection from './components/SliderSection.vue'
 import ImageSection from './components/ImageSection.vue'
 import ImgTextSection from './components/ImgTextSection.vue'
 import CardSection from './components/CardSection.vue'
 import BannerSection from './components/BannerSection.vue'
 import TextSection from './components/TextSection.vue'
 import FooterSection from './components/FooterSection.vue'

 export default {
  name: 'App',
  components: {
    HeaderSection,
    SliderSection,
    ImageSection,
    ImgTextSection,
    CardSection,
    BannerSection,
    TextSection,
    FooterSection,
  }
 }
</script>

<style>
  @import "./App.css";
</style>