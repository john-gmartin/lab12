<template>
  <img
      :src="imagenNieto"
      class="profile"
      :alt="altNieto"
    />
</template>

<script setup>
defineProps({
    imagenNieto:{
        type: String,
        default: "Aquí va una imagen."
    },
    altNieto:{
        type:String,
        default: "Aquí va el texto descriptivo de la imagen."
    },
})
</script>

<style>

</style>