<template>
  <div>
    <h1>Olá</h1>
    <p>Meu nome é {{ name }} e trabalho como {{ profissao }}</p>  <!-- Puxando os dados de data -->
  </div>
</template>

<script>
export default {
  name: 'PrimeiroComponente',
  data(){                       /* Para inserir dados no componente */
    return{                     /* Retorna os dados inseridos */
      name: "Maria",            /* Modificou um valor que já existia */
      profissao: "Programadora"
    }
  }
}
</script>

<style scoped>
</style>
