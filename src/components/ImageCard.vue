<template>
  <div
    class="
      w-full
      sm:w-1/2
      lg:w-1/3
      xl:w-1/4
      px-3
      mb-3
      animate__animated animate__fadeInLeft
    "
  >
    <a>
      <div
        class="painel-card rounded-md relative flex justify-center items-center"
      >
        <search-circle-icon
          class="
            painel-card-icon
            hidden
            absolute
            text-white
            h-14
            animate__animated animate__fadeInLeft
          "
        />
        <img :src="imageSrc" :alt="imageAlt" class="rounded-md relative" />
      </div>
    </a>
  </div>
</template>

<script setup>
import { SearchCircleIcon } from "@heroicons/vue/solid";

defineProps({
  imageAlt: String,
  imageSrc: String,
});
</script>

<style scoped>
.painel-card:hover {
  box-shadow: inset 0 0 0 100vh rgba(0, 0, 0, 0.45);
}

.painel-card:hover img {
  z-index: -1;
}

.painel-card:hover .painel-card-icon {
  display: block;
}
</style>
