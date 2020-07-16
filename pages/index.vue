<template>
  <div>
      <navbar />
      <home />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar/Navbar.vue";
import Home from "@/components/Home/Home.vue";
export default {
  components: {
    Navbar,
    Home
  }
}
</script>
<style scoped>

</style>