<template>
  <form action="" @submit="validate">
    <input
      type="text"
      name="nome"
      placeholder="Nome completo"
      class="rounded block w-full border-gray-300 shadow-sm"
      required
    />
    <input
      type="text"
      name="serventia"
      placeholder="Serventia"
      class="rounded block w-full border-gray-300 shadow-sm mt-3"
    />
    <input
      type="text"
      name="cidade"
      placeholder="Cidade"
      class="rounded block w-full border-gray-300 shadow-sm mt-3"
    />
    <input
      type="tel"
      name="telefone"
      placeholder="Telefone"
      class="rounded block w-full border-gray-300 shadow-sm mt-3"
      required
    />
    <input
      type="email"
      name="email"
      placeholder="E-mail"
      class="rounded block w-full border-gray-300 shadow-sm mt-3"
      required
    />
    <textarea
      name="mensagem"
      cols="30"
      rows="10"
      placeholder="Mensagem"
      class="rounded block w-full border-gray-300 shadow-sm mt-3"
      required
      minlength="10"
    ></textarea>
    <br />
    <div class="flex justify-end mb-3">
      <label class="inline-flex items-center text-sm">
        <input
          type="checkbox"
          name="aceite-termos"
          class="
            rounded
            border-gray-300
            shadow-sm
            focus:ring focus:ring-offset-0
          "
          @change="btnSendIsDisabled = !btnSendIsDisabled"
        />
        <span class="ml-1">
          Li e estou de acordo com as
          <a href="" target="_blank">Políticas de privacidade</a>
        </span>
      </label>
    </div>
    <div class="mt-2 flex justify-end">
      <button
        type="submit"
        class="flex items-center disabled:opacity-50 disabled:cursor-default"
        :disabled="btnSendIsDisabled"
      >
        <img
          class="mr-1"
          src="https://skybind.com.br/assets/img/skybind/Icon-Enviar.svg"
          alt=""
        />
        Enviar
      </button>
      <button type="reset" class="flex items-center ml-6">
        <img
          class="mr-1"
          src="https://skybind.com.br/assets/img/skybind/Icon-Limpar.svg"
          alt=""
        />
        Limpar
      </button>
    </div>
  </form>
</template>

<script setup>
import { ref } from "vue";
let btnSendIsDisabled = ref(true);
</script>

<style scoped>
input:valid {
  border-color: green;
}

input:invalid {
  border-color: red;
}
</style>
