<template>
  <section id="banner" class="text-white pt-24 flex justify-center pb-10">
    <div class="pt-24 flex px-10">
      <div class="w-7/12 pl-6 flex justify-start items-center">
        <img
          src="https://www.skybind.com.br/assets/img/hero/img-laptop-smartphone.png"
          alt="logo-banner"
        />
      </div>
      <div class="w-5/12 tracking-normal text-center">
        <h1 class="font-normal">
          Tenha um site fácil de atualizar que atenda à Resolução nº 389/2021.
        </h1>
        <p
          class="
            border border-solid border-white
            rounded-xl
            mt-9
            py-3
            text-2xl
            font-extralight
            transition-all
            ease-linear
          "
        >
          Solicite uma proposta:<br />
          <strong>(51) 99133-1125</strong><br />
          <strong>(51) 3057-8100</strong> <span>opção</span> <strong>2</strong>
        </p>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style lang="postcss" scoped>
#banner {
  height: 550px;
  background-image: url(https://www.skybind.com.br/assets/img/hero/imagem1.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}

#banner h1 {
  font-size: 32px;
}

#banner p:hover {
  font-size: 26px;
}
</style>
