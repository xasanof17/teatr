<template>
  <header class="header">
    <AsideVue />
    <NavbarVue />
  </header>
</template>

<script>
import NavbarVue from "./Navbar.vue";
import AsideVue from "./Aside.vue";
export default {
  name: "Header",
  components: {
    NavbarVue,
    AsideVue,
  },
};
</script>

<style scoped>
.header{
  position: relative;
  height: 100vh;
  background: url('../assets/img/header.png') no-repeat center / cover;
}
</style>