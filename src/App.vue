<template>
  <div id="app" class="">
    <inicio/>

    <nosso-evento/>

    <programacao/>

    <div class="px-8 md:px-16 py-16 bg-gray-300 text-left text-xs">
      <p class="font-bold">Comissão Central</p>
      <p v-for="pessoa of central" :key="pessoa">
        {{ pessoa }}
      </p>

      <p class="font-bold mt-4">Comissão Acadêmico-Científica</p>
      <p v-for="pessoaA of academico" :key="pessoaA">
        {{ pessoaA }}
      </p>
    </div>
  </div>
</template>

<script>

import "./assets/css/main.css"
import inicio from "./components/inicio";
import nossoEvento from "./components/nossoEvento";
import programacao from "./components/programacao";

export default {
  name: 'app',
  components: {
    inicio,
    nossoEvento,
    programacao
  },
  data: () => {
    return {
      central: ['Presidente Dr. RENATO PADOVESI (REITORIA)',
      'Coordenadora Geral Mariana Brito (REITORIA + PROAC)',
      'Arthur Lima (ASPED)',
      'Prof. Arthur Souto (COORD. DIREITO)',
      'Prof. Antônio Toscano (COORD. DIREITO)',
      'Profª Waleska Vasconcelos (COORD. DIREITO)',
      'Prof. Felipe Soares (COORD. UBTECH + TI)',
      'Prof. Glauber Lucena (COORD. MESTRADO)'],
      academico: ['Profª Lucilene Solano',
      'Prof. Antônio Carlos Coelho',
      'Prof. Paulo Henrique',
      'Profª Maria Marconiete',
      'Profª Sulamita Nóbrega',
      'Prof. Julian Nogueira',
      'Prof. Romulo Palitot',
      'Prof. André Fonseca',
      'Prof. Gerardo Gallo',
      'Prof. Flávia de Paiva',
      'Prof. Francisco Leite',
      'Prof. Marcio Cabral',
      'Profª Kaiana Vilar',
      'Profª Mirella Braga',
      'Profª Simone Torquato',
      'Profª Micheline Carvalho',
      'Prof. Carlos Bráulio',
      'Prof. Felipe Negreiros',
      'Prof. Diêgo Cabral',
      'Profª Maria Cristina Santiago',
      'Prof. Dostoievsky Andrade',
      'Profª Lara Sanábria',
      'Prof. Cláudio Lameirão',
      'Prof. Edigardo Neto',
      'Raffael Costa'
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
