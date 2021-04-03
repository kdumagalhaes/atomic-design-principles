<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Excepturi minus omnis consectetur veritatis optio. Repellat dolorem, consectetur amet ea sunt dolore facilis eius officia explicabo dignissimos eveniet, expedita minima esse!"
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Excepturi minus omnis consectetur veritatis optio. Repellat dolorem, consectetur amet ea sunt dolore facilis eius officia explicabo dignissimos eveniet, expedita minima esse!"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Excepturi minus omnis consectetur veritatis optio. Repellat dolorem, consectetur amet ea sunt dolore facilis eius officia explicabo dignissimos eveniet, expedita minima esse!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: {
    Service
  }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
