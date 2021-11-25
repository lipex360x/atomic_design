<template>
  <div>
    <Container>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat
        provident sunt necessitatibus porro, beatae libero, alias voluptatibus
        temporibus, rerum quas suscipit voluptatum fugiat delectus ad doloribus
        tenetur. Error, quasi sapiente.
      </p>
    </Container>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Container } from '@/components/bosons'

export default defineComponent({
  components: { Container }
})
</script>
