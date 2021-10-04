<template>
  <div class="fixed">
    <cookie-alert />
    <div class="w-full bg-white flex flex-col justify-center items-center">
      <div class="container flex justify-between px-2 md:px-14 py-5">
        <a href="">
          <div class="logo"></div>
        </a>
        <menu-items />
      </div>
    </div>
  </div>
</template>

<script setup>
import CookieAlert from "./CookieAlert.vue";
import MenuItems from "./MenuItems.vue";
</script>

<style lang="postcss" scoped>
.logo {
  mask: url(https://www.skybind.com.br/assets/img/skybind/Logo-Skybind.svg);
  background-color: #0279ae;
  height: 55px;
  width: 193px;
}
</style>
