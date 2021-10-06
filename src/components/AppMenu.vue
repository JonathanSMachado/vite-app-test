<template>
  <div
    id="app-menu"
    class="w-screen bg-white flex flex-col justify-center items-center"
  >
    <div class="w-full flex justify-between px-2 lg:px-16 py-5">
      <a href="" class="pl-3">
        <div class="logo"></div>
      </a>
      <menu-items />
    </div>
  </div>
</template>

<script setup>
import MenuItems from "./MenuItems.vue";

window.onscroll = function (evt) {
  const menu = document.getElementById("app-menu");
  const distance = document.documentElement.scrollTop;

  if (distance > 0) {
    menu.classList.add("shadow-md");
  } else {
    menu.classList.remove("shadow-md");
  }
};
</script>

<style lang="postcss" scoped>
.logo {
  mask: url(https://www.skybind.com.br/assets/img/skybind/Logo-Skybind.svg);
  background-color: #0279ae;
  height: 55px;
  width: 193px;
}
</style>
