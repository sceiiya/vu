<script setup lang="ts">
defineProps<{
  glam: string
}>()
</script>

<template>
  <section id="dissec">
    <div>
      <p>
        Shadow {{ glam }}
      </p>
    </div>
  </section>
</template>

<style>
#dissec {
  color: blanchedalmond;
  background-color: blanchedalmond;
}
</style>
