<script setup lang="ts">
import { ref } from 'vue'
import SceiiyaComponent from '@/components/SceiiyaComponent.vue'
const ct = ref(9)
</script>

<template>
  <main>
    <SceiiyaComponent
      name="Sceiiya"
      message="I'm searching for a specific cosmic child"
      github="https://github.com"
      porfolio="https://yesimscheidj.rocks"
    />
  </main>
  <div class="momo">
    <button @click="ct++">DEEZ is NUMBER U CLICKED! {{ ct }}</button>
  </div>
</template>

<style>
main {
  width: 100%;
  height: 100%;
  background-color: azure;
}

.momo {
  background-color: blueviolet;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px, 0;
}

.momo > button {
  background-color: yellowgreen;
  padding: 6px 2px;
  color: aquamarine;
}
</style>
