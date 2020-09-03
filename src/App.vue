<template>
  <div id="app">

    <!-- v-if/v-else with v-once -->
    <div v-if="true"
         v-once
    >
      a
    </div>
    <div v-else v-once>
      b
    </div>

    <!-- v-once inside v-for -->
    <div v-for="i in 5"
         :key="i">
      <div v-once
           :id="i"
      >
        {{ i }}
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

