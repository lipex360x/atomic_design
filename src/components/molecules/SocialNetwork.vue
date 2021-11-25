<template>
  <section>
    <SocialLink name="Github" icon="github.svg" to="https://github.com" />
    <SocialLink name="Twitter" icon="twitter.svg" to="https://twitter.com" />
    <SocialLink name="Facebook" icon="facebook.svg" to="https://facebook.com" />
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
  components: { SocialLink }
})
</script>

<style lang="scss" scoped>
section {
  display: grid;
  grid-gap: 1rem;
}
</style>
