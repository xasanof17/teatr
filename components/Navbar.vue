<template>
  <nav class="header__nav fixed top-0 left-0 w-full">
    <div class="container mx-auto">
      <div class="header__nav-content flex items-center justify-between flex-wrap py-10">
        <ul class="header__nav-content_list flex justify-start 2xl:w-3/4">
          <li class="header__nav-content_item mx-8">
            <a href="#!" class="header__nav-content_link">Главная</a>
          </li>
          <li class="header__nav-content_item mx-8">
            <a href="#!" class="header__nav-content_link">о театре</a>
          </li>
          <li class="header__nav-content_item mx-8">
            <a href="#!" class="header__nav-content_link">Наши постановки</a>
          </li>
          <li class="header__nav-content_item mx-8">
            <a href="#!" class="header__nav-content_link">партнеры театра</a>
          </li>
          <li class="header__nav-content_item mx-8">
            <a href="#!" class="header__nav-content_link">контакты</a>
          </li>
        </ul>
        <a href="tel:+998900198505" class="header__nav-link"
          >+998 (90) 019-85-05</a
        >
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.header__nav-content_item:nth-of-type(1) {
  margin-left: 0;
}
.header__nav-content_link {
  font-weight: 700;
  font-size: 18px;
  line-height: 25px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--white);
  position: relative;
  padding-bottom: 7px;
}
.header__nav-content_link::before {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 2px;
  background: var(--gold);
  transition: 0.5s ease;
}
.header__nav-content_link:hover {
  text-decoration: none;
}
.header__nav-content_link:hover::before {
  width: 100%;
}
.header__nav-link {
  font-weight: 700;
  font-size: 16px;
  line-height: 22px;
  display: flex;
  align-items: center;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: var(--white);
  padding-bottom: 10px;
  position: relative;
}
.header__nav-link::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 2px;
  background: var(--gold);
  transition: 0.5s ease;
}
.header__nav-link:hover {
  text-decoration: none;
}
.header__nav-link:hover::after {
  width: 0;
}
</style>
