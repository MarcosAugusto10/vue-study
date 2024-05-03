<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral/>
    </div>
    <div class="column is-three-quarter">
  <TarefaComponent/>
  </div>

</main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import TarefaComponent from './components/TarefaComponent.vue';


//teste
export default defineComponent({
  name: 'App',
  components:{
    BarraLateral,
    TarefaComponent
}
  // components: {
  //   HelloWorld
  // }
});
</script>

<style>

</style>
