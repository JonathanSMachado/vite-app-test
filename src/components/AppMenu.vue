<template>
  <div class="fixed">
    <cookie-alert />
    <div class="w-screen bg-white flex flex-col justify-center items-center">
      <div class="w-full flex justify-between px-2 lg:px-16 py-5">
        <a href="" class="pl-3">
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
