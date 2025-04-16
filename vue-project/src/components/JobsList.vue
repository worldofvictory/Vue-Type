
<!--
<script setup lang="ts">
import { ref, onMounted } from 'vue'
const name = ref('Link')
let togle: HTMLElement | null = null;
let circle: HTMLElement | null = null
let checkbox: HTMLInputElement | null = null
let background: HTMLElement | null = null

onMounted(() => {
  togle = document.querySelector(".togle_box");
  circle = document.querySelector('.circle')
  checkbox = document.getElementById('checkbox') as HTMLInputElement
  background = document.querySelector("background");
})


function changeName(newName: string) {
  name.value = newName
}
function handleToggle() {
  togle_boxs()
  changeName('hello')
}

function togle_boxs() {
  if (checkbox?.checked && circle) {
    circle.style.left = "100px";
    togle.style.backgroundColor = "blue"
     name.value;
     if (background) {
      background.style.backgroundColor = "red"; 
    }
  }else{
    circle.style.left = "0px"
  }
}


</script>




  
<template>
  <div class="background_box">
    <div class="element">
      <p>{{ name }}</p>
      
      <label class="togle_box" @click="handleToggle">
        <input type="checkbox" id="checkbox" aria-label="Toggle switch" />
        <div class="circle"></div>
      </label>
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

.togle_box {
  width: 200px;
  height: 100px;
  background-color: black;
  display: block;
  border-radius: 1000px;
  cursor: pointer;
  position: relative;
}
.circle{
position: absolute;
width: 80px;
height: 80px;
background-color: white;
border-radius: 1000px;
margin: 10px;
left: 0px;
transition: 0.5s;
}
input[type="checkbox"]{
  display: none;
}
</style> -->
 