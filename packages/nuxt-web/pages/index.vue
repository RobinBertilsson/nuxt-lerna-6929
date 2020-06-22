<template>
  <div>
    <div>Hello from index!!!!</div>
    <MyButton />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { MyButton } from '@org/vue-scl'

export default Vue.extend({
  components: {
    MyButton
  }
})
</script>
