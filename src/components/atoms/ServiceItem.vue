<template>
  <article>
    <h2>{{ title }}</h2>
    <p>{{ description }}</p>
  </article>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    title: { type: String, required: true },
    description: { type: String, required: true }
  }
})
</script>

<style lang="scss" scoped>
article {
  h2 {
    color: #935e92;
    font-weight: bold;
    margin-bottom: 0.8rem;
  }
  p {
    color: #293947;
    line-height: 1.5;
  }
}
</style>
