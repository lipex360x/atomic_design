<template>
  <div>
    <ServiceList />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { ServiceList } from '@/components/molecules'

export default defineComponent({
  components: { ServiceList }
})
</script>
