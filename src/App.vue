<template>
  <MenuSuperior/>
  <SeletorData></SeletorData>
  <ListaDeBlocos></ListaDeBlocos>
</template>

<script>
import MenuSuperior from './components/MenuSuperior.vue'
import SeletorData from './components/SeletorData.vue';
import ListaDeBlocos from './components/ListaDeBlocos.vue';

export default {
  name: 'App',
  components: {
    MenuSuperior,
    SeletorData,
    ListaDeBlocos
  }
}
</script>

<style>
</style>
