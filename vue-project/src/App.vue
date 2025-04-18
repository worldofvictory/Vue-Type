<script setup lang="ts">
import {ref} from 'vue';
let count = ref<number>(100);
function addToCount() {
  count.value = count.value +1
} 

  const subtractFromCount = () => {
    count.value = count.value -1
  }

</script>

<template>
  <main>
<div>
  <h4> the corrent count is..</h4>
 <h1>{{ count }}</h1> 
 <button @click="subtractFromCount">-</button>
 <button  @click="addToCount">+</button>
</div>
</main>
</template>




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