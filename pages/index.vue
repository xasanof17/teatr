<template>
  <div class="app">
    <HeaderVue />
  </div>
</template>

<script>
import HeaderVue from "../components/Header.vue";
export default {
  name: "IndexPage",
  components: { HeaderVue },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap");
@import url("../assets/fonts/fonts.css");
:root {
  --font-opencond: "OpenSans-Condensed";
  --font-opensans: "Open Sans";
  --white: #fff;
  --dark: #333333;
  --black: #000;
  --gold: #d1a954;
  --borderColor: #616161;
  --inputBg: #444444;
  --lightDark: rgba(51, 51, 51, 0.75);
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: var(--font-opencond);
  background: var(--dark);
  color: var(--white);
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: var(--font-opensans);
  margin-bottom: 0;
}
ul {
  margin-bottom: 0;
  padding-left: 0;
}
a {
  text-decoration: none;
}
.container {
  max-width: 1320px;
  width: 100%;
  padding: 0 12px;
  margin: 0 auto;
}
</style>
