<template>
  <v-toolbar >
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <v-toolbar-title>Tem Bloco na Rua</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items>
      <v-btn flat @click="changeView('home')">Home</v-btn>
    </v-toolbar-items>
  </v-toolbar>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'MenuSuperior',
  props: {
    msg: String
  }
})

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
