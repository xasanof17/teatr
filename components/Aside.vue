<template>
  <aside class="header__aside fixed top-0 left-0">
    <div class="header__aside-content">
      <p>контактная информация</p>
    </div>
  </aside>
</template>

<script>
export default {
  name: "Aside",
};
</script>

<style scoped>
.header__aside {
  width: 10%;
  height: 100%;
  z-index: 5;
  background: var(--lightDark);
}
.header__aside-content {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
p {
  writing-mode: vertical-rl;
  text-orientation: revert;
}
</style>
