<template>
  <div>
    <SearchBar />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SearchBar } from '@/components/molecules'

export default defineComponent({
  components: { SearchBar }
})
</script>
