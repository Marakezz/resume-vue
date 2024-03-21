<script setup>
import HelloSection from './components/HelloSection.vue'
import MainInfoSection from './components/MainInfoSection.vue'
import VueSection from './components/VueSection.vue'
import ReactSection from './components/ReactSection.vue'
import AboutMeSection from './components/AboutMeSection.vue'
import FooterSection from './components/FooterSection.vue'
import ExperienceSection from './components/ExperienceSection.vue'
document.title = 'Резюме'
</script>

<template>
  <div>
    <HelloSection />
    <MainInfoSection />
    <VueSection />
    <ReactSection />
    <AboutMeSection />
    <!-- <ExperienceSection /> -->
    <FooterSection />
  </div>
</template>
