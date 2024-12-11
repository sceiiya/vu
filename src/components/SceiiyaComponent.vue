<script setup lang="ts">
defineProps<{
  name: string
  message: string
  github: string
  porfolio: string
}>()
</script>

<template>
  <section class="sceiiya">
    <h1>Hi UNIVERSE!</h1>
    <h2>This is {{ name }}</h2>
    <div>
      <p>{{ message }}</p>
    </div>
    <div>
      <ol>
        <li>
          <a :href="github" target="_blank"> meet me at my github </a>
        </li>
        <li>
          <a :href="porfolio" target="_blank"> meet me at my portfolio </a>
        </li>
      </ol>
    </div>
  </section>
</template>

<style>
* {
  color: lightgray;
}

h1 {
  background-color: crimson;
  font-size: 50px;
}
</style>
