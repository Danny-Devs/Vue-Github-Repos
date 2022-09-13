<script setup lang="ts">

</script>

<template>
  <div flex justify-between>
    <div>
      <button px-6 py-2 rounded-lg bg-green mr-4 hover:cursor-pointer shadow-md>
        Home
      </button>
      <button px-6 py-2 rounded-lg bg-green hover:cursor-pointer shadow-md>
        Saved Repos
      </button>
    </div>
    <div>
      <div class="i-carbon-sun dark:i-carbon-moon hover:cursor-pointer" @click="toggleDark()" />
    </div>
  </div>
</template>

<style scoped>

</style>
