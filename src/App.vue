<template>
  <div id="app">
    <div v-if="true"
         v-once
    >
      a
    </div>
    <div v-else v-once>
      b
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

