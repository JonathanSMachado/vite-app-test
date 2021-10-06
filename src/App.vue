<script setup>
import CookieAlert from "./components/CookieAlert.vue";
import AppMenu from "./components/AppMenu.vue";
</script>

<template>
  <div class="fixed top-0">
    <cookie-alert />
    <app-menu />
  </div>
  <section id="banner" class="text-white pt-24 flex justify-center pb-10 mt-16">
    <div class="pt-24 flex px-10">
      <div class="w-7/12 pl-6 flex justify-start items-center">
        <img
          src="https://www.skybind.com.br/assets/img/hero/img-laptop-smartphone.png"
          alt="logo-banner"
        />
      </div>
      <div class="w-5/12 tracking-normal text-center">
        <h1 class="font-normal text-base sm:text-xl md:text-3xl">
          Tenha um site fácil de atualizar que atenda à Resolução nº 389/2021.
        </h1>
        <p
          class="
            border border-solid border-white
            rounded-xl
            mt-9
            py-3
            text-base
            sm:text-xl
            md:text-2xl
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

  <section id="section-2" class="flex justify-center py-24">
    <div class="container">
      <h1 class="uppercase text-3xl font-normal text-center mb-3">
        você no controle do seu site, sem o trabalho extra!
      </h1>
      <p class="text-center font-light text-lg mb-20">
        SKYBIND é objetivo, vá direto para inclusão do seu conteúdo.
        Configuração hospedagem, deixa com a gente!
      </p>
      <div class="flex flex-wrap">
        <div class="flex flex-col items-center w-full sm:w-1/3 px-2">
          <img
            class="h-24"
            src="https://skybind.com.br/assets/img/services/Icon-Responsivo.svg"
            alt="Responsivo"
          />
          <h3 class="mt-5 text-2xl mb-3">100% Responsivo</h3>
          <p class="text-center">
            Seu site estará preparado para qualquer dispositivo: computadores,
            smartphones e tablets.
          </p>
        </div>
        <div
          class="flex flex-col items-center w-full sm:w-1/3 px-2 mt-8 sm:mt-0"
        >
          <img
            class="h-24"
            src="https://skybind.com.br/assets/img/services/Icon-ModelosProntos.svg"
            alt="Modelos prontos"
          />
          <h3 class="mt-5 text-2xl mb-3">Modelos Prontos</h3>
          <p class="text-center">
            Quer apenas inserir conteúdos sem se preocupar com o resto? Sem
            problemas! Quer personalizar um pouco mais escolhendo cores, menus e
            outros recursos? Você escolhe! Quer testar outro modelo? É fácil,
            troque o modelo a qualquer momento mantendo todos os dados já
            inseridos!
          </p>
        </div>
        <div
          class="flex flex-col items-center w-full sm:w-1/3 px-2 mt-8 sm:mt-0"
        >
          <img
            class="h-24"
            src="https://skybind.com.br/assets/img/services/Icon-Hospedagem.svg"
            alt="Hospedagem"
          />
          <h3 class="mt-5 text-2xl mb-3">Hospedagem Própria</h3>
          <p class="text-center">
            Não se preocupe com a hospedagem do seu site, nós cuidamos disso!
          </p>
        </div>
      </div>
    </div>
  </section>

  <section id="section-3" class="flex justify-center py-24">
    <div class="container">
      <p class="text-center font-thin mb-20">
        Com nosso <span class="font-semibold">Painel de Controle</span>, você
        não precisa de nenhum domínio técnico para ter um site completo e
        profissional.
      </p>
      <div class="flex flex-wrap">
        <div class="w-full sm:w-1/3 px-3 mb-3">
          <a>
            <img
              src="https://skybind.com.br/assets/img/painel/1.jpg"
              alt=""
              class="rounded-md"
            />
          </a>
        </div>
        <div class="w-full sm:w-1/3 px-3 mb-3">
          <a>
            <img
              src="https://skybind.com.br/assets/img/painel/2.jpg"
              alt=""
              class="rounded-md"
            />
          </a>
        </div>
        <div class="w-full sm:w-1/3 px-3 mb-3">
          <a>
            <img
              src="https://skybind.com.br/assets/img/painel/3.jpg"
              alt=""
              class="rounded-md"
            />
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Ubuntu:wght@300;400;500;700&display=swap");

* {
  font-family: "Ubuntu", Arial, Helvetica, sans-serif;
  scroll-behavior: smooth;
}

#banner {
  height: 550px;
  background-image: url(https://www.skybind.com.br/assets/img/hero/imagem1.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}

#banner p:hover {
  font-size: 26px;
}

#section-2 {
  background-color: #f1efed;
}

#section-2 h1,
#section-2 h3 {
  color: #0279ae;
}

#section-2 p {
  color: #707070;
}

#section-3 {
  background-color: #f8cd48;
}

#section-3 p {
  color: #294b5c;
  font-size: 26px;
}

#section-3 img {
  border: 1px solid #707070;
}
</style>
