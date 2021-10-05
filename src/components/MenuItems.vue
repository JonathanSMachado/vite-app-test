<template>
  <nav class="self-center">
    <button class="toggle-menu block md:hidden">
      <menu-icon class="h-7 w-7" />
    </button>
    <ul class="hidden md:flex uppercase">
      <li class="px-2 lg:px-4">
        <a
          class="
            sm:text-xs
            md:text-sm
            lg:text-base
            transition-all
            ease-linear
            font-medium
          "
          href=""
          >Início</a
        >
      </li>
      <li class="px-2 lg:px-4">
        <a
          class="
            sm:text-xs
            md:text-sm
            lg:text-base
            transition-all
            ease-linear
            font-medium
          "
          href=""
          >Serviços</a
        >
      </li>
      <li class="px-2 lg:px-4">
        <a
          class="
            sm:text-xs
            md:text-sm
            lg:text-base
            transition-all
            ease-linear
            font-medium
          "
          href=""
          >Modelos</a
        >
      </li>
      <li class="px-2 lg:px-4">
        <a
          class="
            sm:text-xs
            md:text-sm
            lg:text-base
            transition-all
            ease-linear
            font-medium
          "
          href=""
          >Clientes</a
        >
      </li>
      <li class="px-2 lg:px-4">
        <a
          class="
            sm:text-xs
            md:text-sm
            lg:text-base
            transition-all
            ease-linear
            font-medium
          "
          href=""
          >Sobre</a
        >
      </li>
      <li class="px-2 lg:px-4">
        <a
          class="
            sm:text-xs
            md:text-sm
            lg:text-base
            transition-all
            ease-linear
            font-medium
          "
          href=""
          >Tutoriais</a
        >
      </li>
      <li class="px-2 lg:px-4">
        <a
          class="
            sm:text-xs
            md:text-sm
            lg:text-base
            transition-all
            ease-linear
            font-medium
          "
          href=""
          >Contato</a
        >
      </li>
    </ul>
  </nav>
</template>

<script setup>
import { MenuIcon } from "@heroicons/vue/solid";
</script>

<style lang="postcss" scoped>
nav > ul > li > a {
  color: #0279ae;
}

nav > ul > li > a:hover {
  border-bottom: 3px solid #0279ae;
}

.toggle-menu {
  color: #0279ae;
}
</style>
