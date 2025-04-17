<template>
  <main>
<div>
  <h4> the corrent count is..</h4>
 <h1>{{ count }}</h1> 
 <button @click="count--">-</button>
 <button  @click="count++">+</button>
</div>
</main>
</template>


<script setup lang="ts">
import {ref} from 'vue';
let count = ref<number>(0);
</script>

<style scoped>
main {
  background-color: #f2f2f2;
  width: 100vw;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
div{
  text-align: center;
}
</style>