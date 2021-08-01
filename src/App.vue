<template>
  <div class="w-full h-28 text-gray-600 bg-primary">
    <router-view />
  </div>
</template>

<script>
import AOS from "aos";
import "aos/dist/aos.css";
export default {
  mounted() {
    AOS.init();
  }
};
</script>
