<template>
  <header>
    <Logo />
    <NavBar />
    <SearchBar />
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from '@/components/atoms'
import { NavBar, SearchBar } from '@/components/molecules'

export default defineComponent({
  components: { Logo, NavBar, SearchBar }
})
</script>

<style lang="scss" scoped>
header {
  width: 100%;
  display: grid;
  grid-template-columns: 160px repeat(2, auto);
  align-items: center;
  justify-content: space-between;
}
</style>
