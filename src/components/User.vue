<template>
 <span class="user">
    <span class="name">{{ nameNieto }}</span>
    <span class="handle">{{ handleNieto }}</span>
 </span>
</template>

<script setup>
defineProps({
    nameNieto:{
        type:String,
        default: "Aquí va el nombre del perfil.",
    },
    handleNieto:{
        type:String,
        default:"Aquí va el nombre de usuario.",
    },
});
</script>

<style>

</style>