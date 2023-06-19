<template>
  <NavBar/>
  <LandingPage/>
  <AboutPage/>
  <ResumePage/>
  <ProjectPage/>
  <TestimonialsPage/>
  <ContactPage/>
  <Footer/>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import LandingPage from '@/components/LandingPage.vue';
import AboutPage from '@/components/AboutPage.vue';
import ResumePage from '@/components/ResumePage.vue';
import ProjectPage from '@/components/ProjectPage.vue';
import TestimonialsPage from '@/components/TestimonialsPage.vue';
import ContactPage from '@/components/ContactPage.vue';
import Footer from '@/components/Footer.vue';

export default {
  components: {
    NavBar,
    LandingPage,
    AboutPage,
    ResumePage,
    ProjectPage,
    TestimonialsPage,
    ContactPage,
    Footer
  }

}
</script>

<style scoped>

</style>