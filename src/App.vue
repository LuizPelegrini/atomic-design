<template>
  <div class="component">
    <Presentation />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Presentation } from '@/components/organisms';

export default defineComponent({
  components: {
    Presentation
  }
});
</script>

<style lang="scss" scoped>
.component {
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
  padding: 0 1rem;
}
</style>
