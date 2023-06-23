<template>
    <p class="message">{{ mensajeNieto }}</p>
</template>

<script setup>
defineProps({
    mensajeNieto:{
        type: String,
        default: "Aquí va un mensaje",
    }
})
</script>

<style>

</style>