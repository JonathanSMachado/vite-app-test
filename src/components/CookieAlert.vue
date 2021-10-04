<template>
  <div
    class="
      message-container
      flex flex-col
      md:flex-row
      justify-center
      items-center
      w-full
      px-5
      md:px-10
      py-1
      md:py-2
      text-sm
    "
  >
    <p class="text-justify font-thin">
      Este site armazena cookies no seu dispositivo para melhorar a navegação e
      permitir a análise do uso do site, contribuindo com as nossas iniciativas
      de marketing. Ao clicar em <strong>"Prosseguir"</strong>, você concorda
      com a nossa
      <a class="transition-all font-medium hover:underline" href="http://">
        Política de Privacidade e Proteção de dados.
      </a>
    </p>
    <button
      class="
        flex
        md:ml-5
        mt-2
        md:mt-0
        px-5
        py-3
        rounded-md
        self-center
        text-white
        font-semibold
        transition-all
        ease-linear
      "
    >
      <check-icon class="h-5 w-5" />
      Prosseguir
    </button>
  </div>
</template>

<script setup>
import { CheckIcon } from "@heroicons/vue/solid";
</script>

<style lang="postcss" scoped>
.message-container {
  background-color: #f1efed;
}

.message-container button {
  background-color: #0279ae;
}

.message-container button:hover {
  background-color: #239fd4;
}

.message-container p > a {
  color: #0279ae;
}

.message-container p {
  color: #294b5c;
}
</style>
