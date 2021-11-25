<template>
  <a :href="to">
    <img :src="iconPath" alt="name" />
  </a>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    name: { type: String, required: true },
    icon: { type: String, required: true },
    to: { type: String, required: true }
  },

  computed: {
    iconPath() {
      return require(`@/assets/images/icons/${this.icon}`)
    }
  }
})
</script>

<style lang="scss" scoped>
a {
  background-color: #ff895f;
  width: 47px;
  height: 47px;
  border-radius: 5rem;
  display: grid;
  justify-items: center;
  align-items: center;
  transition: transform 0.1s linear;
  &:hover {
    transform: scale(1.04);
  }
  img {
    width: 23px;
    height: 23px;
  }
}
</style>
