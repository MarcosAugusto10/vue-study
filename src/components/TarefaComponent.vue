<template>
<body>
    <div class="section" >
        <!-- Botão Play -->
        
        <input type="text" id="nome" name="nome" placeholder="Digite a tarefa que você quer iniciar" class="label">
        <!--<p id="timer-display" class="subtitle timer">00:00:00</p>-->
        <button class="button is-success botao">
            <span class="icon is-small">
                <i class="fas fa-play"></i>
            </span>
            <span>Play</span>
        </button>

        <!-- Botão Stop -->
        <button class="button is-danger botao">
            <span class="icon is-small">
                <i class="fas fa-stop"></i>
            </span>
            <span>Stop</span>
        </button>
    </div>
</body>
</template>
<script lang='ts'>
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'TarefaComponent'
})
</script>

<style scoped>
.botao 
{
    float: right;
}
.label
{
    width: 600px;
    height: 20px;
    float: left;
}
.timer
{
font-size: 10px;
}
</style>