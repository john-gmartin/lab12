<template>
  <span class="timestamp" >{{ timestampNieto }}</span>
</template>

<script setup>
defineProps({
    timestampNieto:{
        type: String,
        default: "Aquí va el timestamp.",
    },
})
</script>

<style>

</style>