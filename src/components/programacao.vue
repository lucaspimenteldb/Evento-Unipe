<template>
  <div class="w-full pb-24">
    <article class="px-8 md:px-16 md:pt-16 flex">
      <h3 class="text-2xl font-bold text-left mb-4">Programação</h3>
    </article>

    <!--Lista de palestrantes-->
    <section class="relative px-8 md:px-16 flex flex-col text-left">
      <article v-for="evento of eventos" :key="evento" class="mb-6 relative">
        <div class="relative mb-1 font-bold">
          <span class="w-16 h-2 mt-2 bg-orange-400 absolute z-10 etiqueta"></span>
          <p class="ml-2">{{ evento.dia }} {{evento.horário}}</p>
        </div>

        <div class="ml-4 font-bold">
          <p>Evento: {{ evento.evento }}</p>
        </div>

        <div v-for="palestrante of evento.palestrantes" :key="palestrante" class="ml-4">
          <p>{{ palestrante }}</p>
        </div>

        <img src="../assets/img/calendario.png" alt="calendario" width="30" class="absolute top-0 right-0">
        <hr>
      </article>
    </section>
  </div>
</template>

<script>
  export default {
    name: "programacao",
    data: () => {
      return {
        eventos: [
          {
            dia: '10/02',
            evento: 'Solenidade de Abertura',
            palestrantes: ['Min. Ricardo Lewandowski'],
            horário: '- Manhã e noite'
          },
          {
            dia: '11/02',
            evento: 'Palestras',
            palestrantes: ['Dr. Sérgio Queiroz', 'Dr. Eitel Santiago'],
            horário: '- Manhã e Noite'
          },
          {
            dia: '12/02',
            evento: 'Hackaton',
            palestrantes: ['Prof. Felipe Soares'],
            horário: '- Manhã e Noite'
          },
          {
            dia: '13/02',
            evento: 'Palestras',
            palestrantes: ['Min. Paulo Dias de Moura Ribeiro', 'Dr. Des. Rogério Fialho', 'Dr. Bruno Teixeira'],
            horário: '- Manhã e Noite'
          },
          {
            dia: '14/02',
            evento: 'Palestras',
            palestrantes: ['Min. José Roberto Pimenta', 'Des. Dr. Wolney Cordeiro', 'Juiz Dr. Paulo Henrique'],
            horário: '- Manhã e Noite'
          },


        ]
      }
    }
  }
</script>

<style scoped>
  .etiqueta {
    left: -3rem;
    z-index: -1;
  }
</style>
