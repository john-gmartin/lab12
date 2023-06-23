<template>
  <div class="tweet">
    <Image :imagenNieto="imagenPadre" :altNieto="altPadre" />

    <div class="body">
      <div class="top">
        <user :nameNieto="namePadre" :handleNieto="handlePadre"/>
        <timestamp :timestampNieto="timestampPadre" />
      </div>

      <message :mensajeNieto="mensajePadre"/>
    

      <div class="actions">
        <!-- Font Awesome icons -->
        <i class="far fa-comment"></i>
        <i class="fas fa-retweet"></i>
        <i class="far fa-heart"></i>
        <i class="fas fa-share"></i>
      </div>
    </div>

    <i class="fas fa-ellipsis-h"></i>
  </div>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>

<script setup>

import Image from "./Image.vue";
import Message from "./Message.vue";
import User from "./User.vue";
import Timestamp from "./Timestamp.vue";

defineProps({
  imagenPadre:{
    type:String,
  },
  mensajePadre:{
    type:String,
  },
  namePadre:{
    type:String,
  },
  handlePadre:{
    type:String,
  },
  timestampPadre:{
    type:String,
  },
});

</script>
