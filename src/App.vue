<template>
  <HeaderSection />
  <SliderSection />
  <ImageSection skill="section" />
  <ImgTextSection skill="section" />
</template>

<script>
 import HeaderSection from './components/HeaderSection.vue'
 import SliderSection from './components/SliderSection.vue'
 import ImageSection from './components/ImageSection.vue'
 import ImgTextSection from './components/ImgTextSection.vue'

 export default {
  name: 'App',
  components: {
    HeaderSection,
    SliderSection,
    ImageSection,
    ImgTextSection
  }
 }
</script>

<style>
  @import "./App.css";
</style>