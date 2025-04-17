<!--<script setup lang="ts">
import ComputedUser from './ComputedUser.vue'
import { ref} from 'vue'
const name = ref('Hello');
function changeName(newName: string) {
  name.value = newName
}
</script>
 
<template>
<div>
    <ComputedUser />
  
  <div class="background_box">
    <div class="element">
      <p>{{ name }}</p>
      <button @click="changeName('Goodbye')"> change </button>
    </div>
    </div>
  </div>
</template>

<style scoped>
.element {
  display: flex;
  gap: 20px;
}

.background_box {
  width: 100%;
  height: 100vh;
  background-color: white;
  display: flex;
  align-items: center;
  justify-content: center;
}

</style>-->