<template>
  <section>
    <ServiceItem
      title="Backend"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio numquam expedita nemo iusto porro blanditiis maxime asperiores doloremque, commodi earum nihil, hic deserunt et dolore iste mollitia consequatur perspiciatis tempore"
    />

    <ServiceItem
      title="Frontend"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio numquam expedita nemo iusto porro blanditiis maxime asperiores doloremque, commodi earum nihil, hic deserunt et dolore iste mollitia consequatur perspiciatis tempore"
    />

    <ServiceItem
      title="Mobile"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio numquam expedita nemo iusto porro blanditiis maxime asperiores doloremque, commodi earum nihil, hic deserunt et dolore iste mollitia consequatur perspiciatis tempore"
    />
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { ServiceItem } from '@/components/atoms'
export default defineComponent({
  components: { ServiceItem }
})
</script>

<style lang="scss" scoped>
section {
}
</style>
