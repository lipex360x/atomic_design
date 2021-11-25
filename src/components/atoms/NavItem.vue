<template>
  <a :href="to">{{ text }}</a>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    text: { type: String, required: true },
    to: { type: String, required: true }
  }
})
</script>

<style lang="scss" scoped>
a {
  color: #293947;
  text-decoration: none;
  font-size: 1.3rem;
}
</style>
