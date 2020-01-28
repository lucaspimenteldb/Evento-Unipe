<template>
  <div class="w-full pb-16">
    <section class="px-8 pt-8 md:px-16 md:pt-16 flex relative">
      <img src="../assets/img/fundo-evento.png" alt="Evento" class="object-cover hidden md:w-1/2 md:block">

      <article class="w-full md:w-2/5 md:ml-4 text-left nosso-evento">
        <h3 class="text-2xl font-bold">Nosso Evento</h3>
        <p>
          Teremos diversas atividade, partindo desde a apresentação de Trabalhos Científicos a Hackatons. <span class="font-medium"> Nós teremos apenas 500 vagas </span>para garantir uma maior eficiência e aprendizado a todos.
        </p>

        <p class="font-bold mt-2">Temas Paralelos</p>
        <p>
          <span class="w-2 h-2 mt-2 border-2 border-orange-400 rounded-full absolute z-10"></span>
          <span class="relative z-40 ml-4 whitespace-no-wrap"></span>
          Reforma Trabalhista
        </p>

        <p>
          <span class="w-2 h-2 mt-2 border-2 border-orange-400 rounded-full absolute z-10"></span>
          <span class="relative z-40 ml-4 whitespace-no-wrap "></span>
          Reforma Previdenciária
        </p>

        <p>
          <span class="w-2 h-2 mt-2 border-2 border-orange-400 rounded-full absolute z-10"></span>
          <span class="relative z-40 ml-4 whitespace-no-wrap"></span>
          Reforma Criminal (Combate a corrupção)
        </p>
      </article>
    </section>
  </div>
</template>

<script>
  export default {
    name: "nossoEvento"
  }
</script>

<style scoped>
  .nosso-evento::before {
    content: '';
    width: 10rem;
    height: 8rem;
    top: 0;
    left: 0;
    position: absolute;
    z-index: -1;
    background: rgba(251, 148, 72, 0.4);

  }
</style>
