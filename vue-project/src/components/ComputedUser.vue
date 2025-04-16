<template>
    <div>
      <label>Nome utente (in maiuscolo):</label>
      <input v-model="nomeUppercase" />
      <p>Nome originale: {{ nome }}</p>
    </div>
  </template>
  
  <script setup lang="ts">
  import { ref, computed } from 'vue'
  
 
  
  // Dato originale (ref)
  const nome = ref('')
  
  // Computed con getter e setter
  const nomeUppercase = computed({
    get() {
      return nome.value.toLowerCase()
    },
    set(val: string) {
      // Quando l'utente digita qualcosa, lo salviamo 
      nome.value = val.toUpperCase()
    }
  })

  </script>