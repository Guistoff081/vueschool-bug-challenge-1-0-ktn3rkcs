<template>
  <div class="decoder-input">
    <AlienMessage />
    <DecoderInput v-model="model" />
  </div>
</template>

<script setup>
import AlienMessage from './AlienMessage.vue';
import DecoderInput from './DecoderInput.vue';

const model = defineModel();
</script>

<style scoped>
.decoder-input {
  margin: 20px 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
}
</style>
