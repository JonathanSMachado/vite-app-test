<script setup>
import CookieAlert from "./components/CookieAlert.vue";
import AppMenu from "./components/AppMenu.vue";
import ImageCard from "./components/ImageCard.vue";
import ContactForm from "./components/ContactForm.vue";
</script>

<template>
  <div class="fixed top-0 z-50">
    <cookie-alert />
    <app-menu />
  </div>
  <section id="banner" class="text-white pt-48 pb-10 mt-12">
    <div class="container flex mx-auto">
      <div class="hidden w-7/12 lg:pl-6 md:flex justify-start items-center">
        <img
          src="https://www.skybind.com.br/assets/img/hero/img-laptop-smartphone.png"
          alt="logo-banner"
        />
      </div>
      <div
        class="
          w-full
          md:w-5/12
          tracking-normal
          text-center
          pt-10
          md:pt-0
          lg:mr-20
        "
      >
        <h1 class="font-normal text-base text-3xl">
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

  <section id="section-2" class="py-24">
    <div class="container m-auto lg:px-16">
      <h1 class="uppercase text-3xl font-normal text-center mb-3">
        você no controle do seu site, sem o trabalho extra!
      </h1>
      <p class="text-center font-light text-lg mb-20">
        SKYBIND é objetivo, vá direto para inclusão do seu conteúdo.
        Configuração hospedagem, deixa com a gente!
      </p>
      <div class="flex flex-wrap text-center">
        <div class="flex flex-col items-center w-full sm:w-1/3 px-2">
          <img
            class="h-24"
            src="https://skybind.com.br/assets/img/services/Icon-Responsivo.svg"
            alt="Responsivo"
          />
          <h3 class="mt-5 text-2xl mb-3">100% Responsivo</h3>
          <p>
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
          <p>
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
          <p>
            Não se preocupe com a hospedagem do seu site, nós cuidamos disso!
          </p>
        </div>
      </div>
    </div>
  </section>

  <section id="section-3" class="py-24">
    <div class="container mx-auto lg:px-14">
      <p class="text-center font-thin mb-20">
        Com nosso <span class="font-semibold">Painel de Controle</span>, você
        não precisa de nenhum domínio técnico para ter um site completo e
        profissional.
      </p>
      <div class="flex flex-wrap justify-center">
        <image-card
          imageSrc="https://skybind.com.br/assets/img/painel/1.jpg"
          class="w-full sm:w-1/2 lg:w-1/3"
        />
        <image-card
          imageSrc="https://skybind.com.br/assets/img/painel/2.jpg"
          class="w-full sm:w-1/2 lg:w-1/3"
        />
        <image-card
          imageSrc="https://skybind.com.br/assets/img/painel/3.jpg"
          class="w-full sm:w-1/2 lg:w-1/3"
        />
      </div>
    </div>
  </section>

  <section id="section-4" class="py-24">
    <div class="container mx-auto text-center lg:px-14">
      <h1 class="uppercase text-3xl mb-1">
        Escolha entre modelos pré-formatados
      </h1>
      <p class="text-2xl">Sem programação, sem complicação.</p>
      <div class="flex flex-wrap mt-8 justify-center">
        <image-card
          imageSrc="https://skybind.com.br/assets/img/portfolio/modelo1.webp"
          class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4"
        />
        <image-card
          imageSrc="https://skybind.com.br/assets/img/portfolio/modelo2.webp"
          class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4"
        />
        <image-card
          imageSrc="https://skybind.com.br/assets/img/portfolio/modelo3.webp"
          class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4"
        />
        <image-card
          imageSrc="https://skybind.com.br/assets/img/portfolio/modelo4.webp"
          class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4"
        />
      </div>
    </div>
  </section>

  <section id="section-5" class="py-24">
    <div class="container mx-auto flex px-6 lg:px-16">
      <div class="lg:w-1/2">
        <h1 class="uppercase text-3xl mb-12 text-white text-center">
          Como funciona?
        </h1>
        <p class="mb-2 text-justify">
          <strong>SKYBind</strong> é um serviço de website e hospedagem
          exclusivo para Serventias que desejam ter e manter um site alinhado
          com suas necessidades, de forma rápida e prática, preparados para
          atender a <strong>Resolução nº 389/2021</strong>, que determina que
          sites de Cartórios tenham uma aba "Transparência" para divulgar,
          mensalmente, informações sobre o valor obtido com emolumentos
          arrecadados e outras receitas, bem como o valor total de suas
          despesas.
        </p>
        <p class="mb-2 text-justify">
          <strong>SKYBind</strong> é desenvolvido pela
          <a
            class="font-semibold hover:underline"
            href="https://www.skyinformatica.com.br"
            target="_blank"
          >
            Sky Informática </a
          >, empresa gaúcha que atua há 30 anos exclusivamente no setor
          cartorário, com ampla experiência no segmento.
        </p>
        <p class="mb-2 text-justify">
          A Serventia tem autonomia completa para inserir os conteúdos em suas
          páginas.
        </p>
        <p class="mb-2 text-justify">
          O processo de aquisição é bem simples: defina um domínio para seu site
          e escolha um dos modelos de layouts disponíveis. Assim que tivermos
          essas informações, configuramos o nosso servidor de hospedagem para
          deixar o seu site acessível. Por fim, entramos em contato para
          informar o acesso à área administrava e um treinamento com dicas para
          a inclusão dos conteúdos.
        </p>
      </div>
      <div class="hidden lg:block lg:w-1/2 mt-16">
        <img
          src="https://skybind.com.br/assets/img/about/img-laptop@2x.png"
          alt=""
        />
      </div>
    </div>
  </section>

  <section id="section-6" class="py-24">
    <div class="container mx-auto">
      <h1 class="uppercase text-center text-3xl text-white">Tutoriais</h1>
    </div>
    <div class="flex justify-center mt-6">
      <iframe
        width="800"
        height="600"
        src="https://www.youtube.com/embed/videoseries?list=PLfECappZVayj-abxzD-8nuo57Os34q4gi"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </div>
  </section>

  <section id="section-7" class="py-24">
    <div class="container mx-auto lg:px-8 xl:px-16">
      <h1 class="uppercase text-center text-3xl">Solicite um orçamento!</h1>
      <div class="flex flex-wrap justify-center mt-10">
        <div class="md:w-1/2 flex flex-col items-center px-2">
          <img
            class="h-11"
            src="https://skybind.com.br/assets/img/contact/Icon-Contato.svg"
            alt=""
          />
          <p class="text-2xl mt-2 text-center">
            <strong>(51) 99133-1125</strong> ou
            <strong>(51) 3057-8100</strong> opção <strong>2</strong>
          </p>
          <p class="text-lg text-center mb-8">
            De Seg. à Sex., das 08:30 às 12:00 e das 13:30 às 18h
            <br />
            Ou envie-nos uma mensagem via WhatsApp
          </p>
          <img
            class="h-7"
            src="https://skybind.com.br/assets/img/contact/Icon-Email.svg"
            alt=""
          />
          <p class="text-lg text-center mt-2 mb-8">sky@skyinformatica.com.br</p>
          <div class="flex flex-wrap justify-center mb-7">
            <a
              href="https://pt-br.facebook.com/SkyInformatica/"
              target="_blank"
            >
              <i
                class="
                  fab
                  fa-facebook-f
                  text-white
                  p-4
                  mx-1
                  w-14
                  h-14
                  flex
                  items-center
                  justify-center
                  text-3xl
                "
              ></i>
            </a>
            <a
              href="https://www.youtube.com/channel/UCD1nvXlBCVPOUkcZ2OBi8rw"
              target="_blank"
            >
              <i
                class="
                  fab
                  fa-youtube
                  text-white
                  p-4
                  mx-1
                  w-14
                  h-14
                  flex
                  items-center
                  justify-center
                  text-3xl
                "
              ></i>
            </a>
            <a
              href="https://www.instagram.com/skyinformaticaltda/"
              target="_blank"
            >
              <i
                class="
                  fab
                  fa-instagram
                  text-white
                  p-4
                  mx-1
                  w-14
                  h-14
                  flex
                  items-center
                  justify-center
                  text-3xl
                "
              ></i>
            </a>
            <a href="https://twitter.com/SkyInformatica" target="_blank">
              <i
                class="
                  fab
                  fa-twitter
                  text-white
                  p-4
                  mx-1
                  w-14
                  h-14
                  flex
                  items-center
                  justify-center
                  text-3xl
                "
              ></i>
            </a>
            <a
              href="https://www.linkedin.com/company/skyinformatica/"
              target="_blank"
            >
              <i
                class="
                  fab
                  fa-linkedin-in
                  text-white
                  p-4
                  mx-1
                  w-14
                  h-14
                  flex
                  items-center
                  justify-center
                  text-3xl
                "
              ></i>
            </a>
          </div>
          <img
            src="https://skybind.com.br/assets/img/contact/Icon-Endereco.svg"
            alt=""
          />
          <p class="text-lg text-center mt-2 mb-3 md:mb-0">
            Rodovia BR 470, nº 2751 - Bairro Faxinal
            <br />
            CEP 92515-800 - Montenegro/RS
          </p>
        </div>
        <div class="md:w-1/2 px-2">
          <contact-form />
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div
      class="
        container
        mx-auto
        px-6
        lg:px-12
        py-10
        flex flex-col
        md:flex-row
        items-center
        justify-center
      "
    >
      <a href="#banner" class="text-white">
        <img
          class="p-0 md:pr-4 border-0 md:border-r-2 mb-2 md:mb-0 h-8"
          src="https://skybind.com.br/assets/img/skybind/Logo-Skybind.svg"
          alt=""
        />
      </a>
      <p class="text-sm font-thin mx-6 flex flex-wrap justify-center">
        <span class="m-0 lg:mr-4">
          Desenvolvido por Sky Informática. 2021. Todos os direitos reservados.
        </span>
        <a class="hover:underline" href="">Política de privacidade</a>
      </p>
      <a href="https://www.skyinformatica.com.br" target="_blank">
        <img
          class="p-0 md:pl-4 border-0 md:border-l-2 mt-2 md:mt-0 h-8"
          src="https://skybind.com.br/assets/img/skybind/LogoSky.svg"
          alt=""
        />
      </a>
    </div>
  </footer>
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

#section-4 {
  background-color: #0279ae;
  color: white;
}

#section-5 {
  background-image: url("https://skybind.com.br/assets/img/hero/imagem1.jpg");
}

#section-5 p {
  color: #294b5c;
}

#section-5 a {
  color: #0279ae;
}

#section-6 {
  background-color: #294b5c;
}

#section-7 {
  color: #0279ae;
}

#section-7 p:not(.text-2xl) {
  color: #294b5c;
}

#section-7 a {
  transition: all ease 0.25s;
}

#section-7 a > i {
  background-color: #294b5c;
}

#section-7 a > .fa-facebook-f:hover {
  background-color: #3b5998;
}

#section-7 a > .fa-youtube:hover {
  background-color: #d23a1d;
}

#section-7 a > .fa-instagram:hover {
  background-color: #c13584;
}

#section-7 a > .fa-twitter:hover {
  background-color: #00cafb;
}

#section-7 a > .fa-linkedin-in:hover {
  background-color: #007bb6;
}

footer {
  background-color: #0279ae;
  color: #fff;
}

footer img {
  min-width: 115px;
}
</style>
