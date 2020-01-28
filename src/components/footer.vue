<template>
  <div class="px-8 md:px-16 py-4 bg-gray-300">
    <p>Comissão Central</p>
    <p v-for="pessoa of central" :key="pessoa">
      {{ pessoa }}
    </p>

    <p>Comissão Acadêmico-Científica</p>
    <p v-for="pessoaA of academico" :key="pessoaA">
      {{ pessoaA }}
    </p>
  </div>
</template>

<script>
  export default {
    name: "footer",

  }
</script>

<style scoped>

</style>
