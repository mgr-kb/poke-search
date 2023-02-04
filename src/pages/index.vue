<template>
  <main>
    <h1>Nuxt3 ESLint Prettier</h1>
    <div>
      count: {{ count }}
      <div>
        <button @click="plus">plus</button>
        <button @click="minus">minus</button>
      </div>
    </div>
  </main>
</template>

<script lang="ts" setup>
const count = ref(0);
const plus = () => count.value++;
const minus = () => count.value--;
</script>
