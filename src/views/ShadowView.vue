<script setup lang="ts">
import ShadowComponent from '@/components/ShadowComponent.vue';
import { ref } from 'vue';
const ct = ref(99)
</script>


<template>
  <main>
    <ShadowComponent glam="mongol" />
    <section id="shadsec">
      <div id="shaddiv">
        <button id="tisbutton" @click="ct--">lets count bloody fingies {{ ct }}</button>
      </div>
    </section>
  </main>
</template>

<style>
#shadsec {
  display: flex;
  justify-content: center;
  height: 10px;
  background-color: burlywood;
}

#shaddiv {
  margin: auto;
}

#tisbutton {
  color: palevioletred;
  font-size: 15px;
  height: 10px;
  padding: 10px;
}
</style>
