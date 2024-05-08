<template>
<body>
<div class="divImages">
    <img src="../assets/logo.png">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR-Z5MfPlg1jISWIiTARJcEG4hPWxYYRxeP1D727QsOdQ&s">
    <img src="https://devsagaz.com.br/content/images/2023/05/Ekran-Resmi-2019-11-18-18.08.13.png">
    <img src="https://miro.medium.com/v2/resize:fit:1125/0*CpxR8zt1z6vZDorB.png">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Microsoft_Azure_Logo.svg/2560px-Microsoft_Azure_Logo.svg.png">
</div>
<!--<button class="button is-primary">Primary button</button>-->

<p class="primeiroParagrafo">
Website to track the time of your activities. Developed using Vue, TypeScript, Css-Bulma and Fontawesome. It will be available on an app, developed using React Native. The website will be hosted on Azure and Hostgator. APIs will be developed on ASP .Net and database in the SQL server, and also will be temporary hosted on azure. Open-source material, avaible on github.
</p>
<p class="button is-patreon segundoParagrafo">
    Created by: Marcos Augusto
</p>

</body>
</template>

<script lang='ts'>
import {defineComponent} from 'vue';
export default defineComponent(
{
    name: 'FooterComponent'
})
</script>

<style scoped>
.body
{
    align-items: center;
}
img
{
    width: 100px;
    height: 100px;
    padding: 20px;
}
.divImages
{
    display: flex;
    align-items: center;
    justify-content: center;
}
.primeiroParagrafo
{
font-size: 20px;
padding: 15px;
}
.segundoParagrafo
{
font-size: 15px;
background-color: #969595;
font-style: bold;
display: flex;
    align-items: center;
    justify-content: center;
}
</style>