<template>
  <div>
    <navbar />
    <home />
    <about />
    <services />
    <projects />
    <contact />
    <Foot />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar/Navbar.vue";
import Home from "@/components/Main/Home.vue";
import About from "@/components/Main/About.vue";
import Services from "@/components/Main/Services.vue";
import Projects from "@/components/Main/Projects.vue";
import Contact from "@/components/Main/Contact.vue";
import Foot from "@/components/Main/Foot.vue";
export default {
  components: {
    Navbar,
    Home,
    About,
    Services,
    Projects,
    Contact,
    Foot
  }
};
</script>
<style scoped>
html {
  scroll-behavior: smooth !important;
}
</style>
