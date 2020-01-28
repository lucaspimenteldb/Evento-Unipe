<template>
  <div class="w-full h-auto pb-24">
    <section class="px-8 pt-8 md:px-16 md:pt-16">
      <h1 class="text-3xl font-bold text-left">Direito e Inovação - Unipê 2020.1</h1>
      <p class="mt-2 text-left text-sm">Direito, Desenvolvimento e Inovação: <br>reflexões e desafios da efetividade constitucional</p>
    </section>

    <section class="flex flex-wrap w-full mt-8 px-8 pb-8 md:px-16 ">
      <article class="w-full sm:w-1/3 mt-8">
        <p class="text-left text-lg font-black">Palestrantes</p>
        <p class="text-left text-lg relative z-30">
          <span class="w-6 h-6 px-4 py-4 border-2 border-orange-400 rounded-full absolute"></span>
          <span class="relative z-40 ml-2 whitespace-no-wrap">6+</span>
        </p>
      </article>

      <article class="w-full sm:w-1/3 mt-8">
        <p class="text-left text-lg font-black">Credenciamento</p>
        <p class="text-left text-lg relative z-30">
          <span class="w-6 h-6 px-4 py-4 border-2 border-orange-400 rounded-full absolute"></span>
          <span class="relative z-40 ml-2 whitespace-no-wrap">10 de janeiro, às 8hrs</span>
        </p>
      </article>

      <article class="w-full sm:w-1/3 mt-8">
        <p class="text-left text-lg font-black">Local</p>
        <p class="text-left text-lg relative z-30">
          <span class="w-6 h-6 px-4 py-4 border-2 border-orange-400 rounded-full absolute"></span>
          <span class="relative z-40 ml-2 whitespace-no-wrap">Auditório Unipê</span>
        </p>
      </article>

      <article class="w-full sm:w-1/3 mt-8">
        <p class="text-left text-lg font-black">Palestras</p>
        <p class="text-left text-lg relative z-30">
          <span class="w-6 h-6 px-4 py-4 border-2 border-orange-400 rounded-full absolute"></span>
          <span class="relative z-40 ml-2 whitespace-no-wrap">11 de janeiro, às 9hrs</span>
        </p>
      </article>

      <article class="w-full sm:w-1/3 mt-8">
        <p class="text-left text-lg font-black">Carga Horária</p>
        <p class="text-left text-lg relative z-30">
          <span class="w-6 h-6 px-4 py-4 border-2 border-orange-400 rounded-full absolute"></span>
          <span class="relative z-40 ml-2 whitespace-no-wrap">50 horas, 75% de frequência</span>
        </p>
      </article>
    </section>

    <a href="#" class="px-6 py-4 bg-orange-400 text-center text-black font-bold shadow-md hover:shadow-lg hover:bg-orange-300">Quero me inscrever</a>
  </div>
</template>

<script>
  export default {
    name: "inicio"
  }
</script>

<style scoped>
  div:first-child {
    background: url("../assets/img/fundo-inicio.png") no-repeat 0 top/100%;
  }

  section:nth-of-type(2) {
    background: rgba(186, 253, 255, 0.8);
  }
</style>
