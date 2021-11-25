<template>
  <nav>
    <NavItem text="Services" to="/services" />
    <NavItem text="About me" to="/about" />
    <NavItem text="Cases" to="/cases" />
    <NavItem text="Contact" to="/contact" />
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavItem } from '@/components/atoms'

export default defineComponent({
  components: { NavItem }
})
</script>

<style lang="scss" scoped>
nav {
  width: max-content;
  display: grid;
  grid-auto-flow: column;
  grid-gap: 2.5rem;
}
</style>
