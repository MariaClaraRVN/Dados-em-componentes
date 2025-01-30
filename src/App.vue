<template>
  <HelloWorld/>
  <LifeCycle/>
  <PessoaDescricao/>
  <formInput/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import LifeCycle from './components/LifeCycle.vue';
import PessoaDescricao from './components/PessoaDescricao.vue';
import formInput from'./components/Form/form.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    LifeCycle,
    PessoaDescricao,
    formInput
  }
}
</script>

<style>
</style>
