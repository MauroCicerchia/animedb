<template>
  <div class="bg-indigo-50 dark:bg-gray-900 p-3">
    <h1 class="text-gray-800 dark:text-indigo-50 text-2xl font-semibold">{{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
