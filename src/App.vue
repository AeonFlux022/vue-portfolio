<template>
    <NavigationBar />
    <HeroSection />
    <SpacerBar />
    <SkillsSection />
    <SpacerBar />
    <SampleWorks />
    <SpacerBar />
    <ContactUs />
    <FooterSection />

</template>

<script>
import NavigationBar from './components/NavigationBar.vue';
import HeroSection from './components/HeroSection.vue';
import SpacerBar from './components/SpacerBar.vue';
import SkillsSection from './components/SkillsSection.vue';
import SampleWorks from './components/SampleWorks.vue';
import ContactUs from './components/ContactUs.vue';
import FooterSection from './components/FooterSection.vue';

export default {
  name: 'app',
  components: {
    NavigationBar,
    HeroSection,
    SpacerBar,
    SkillsSection,
    SampleWorks,
    ContactUs,
    FooterSection
}
}
</script>

