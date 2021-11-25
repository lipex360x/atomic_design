<template>
  <section>
    <SocialNetwork />
    <Hero />
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import { SocialNetwork } from '@/components/molecules'
import { Hero } from '@/components/atoms'

export default defineComponent({
  components: { SocialNetwork, Hero }
})
</script>

<style lang="scss" scoped>
section {
  position: relative;
  display: grid;
  justify-content: center;

  section {
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
  }
  img {
    width: 80%;
    justify-self: center;
  }
}
</style>
