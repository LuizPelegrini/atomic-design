<template>
  <div class="component">
    <Service
      title="Frontend"
      description="jhsdhsj hjsh hjsd js djhs hhhh hjsdjs sj "
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
.component {
  width: 300px;
}
</style>
