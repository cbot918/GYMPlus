<script>
import AOS from 'aos';
import 'aos/dist/aos.css';

export default {
  mounted() {
    AOS.init();
  },
};
</script>

<template>
  <RouterView />
</template>

<style scoped lang="scss"></style>
