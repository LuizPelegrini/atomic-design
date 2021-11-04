<template>
  <div class="services">
    <Service
      title="Frontend"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis optio facere eos, expedita repellat nihil ratione magni enim id officiis voluptatum ab placeat, maiores sit ullam ex architecto et veritatis?"
    />
    <Service
      title="Backend"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis optio facere eos, expedita repellat nihil ratione magni enim id officiis voluptatum ab placeat, maiores sit ullam ex architecto et veritatis?"
    />
    <Service
      title="Maintenance"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis optio facere eos, expedita repellat nihil ratione magni enim id officiis voluptatum ab placeat, maiores sit ullam ex architecto et veritatis?"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Service } from '@/components/molecules';

export default defineComponent({
  components: {
    Service
  }
});
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
