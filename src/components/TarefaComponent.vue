<template>
<body>
    <TemporizadorComponent/>
</body>
</template>
<script lang='ts'>
import { defineComponent } from 'vue';
import TemporizadorComponent from './TemporizadorComponent.vue';
export default defineComponent({
    name: 'TarefaComponent',
    components: { TemporizadorComponent }
})
</script>

<style scoped>

</style>