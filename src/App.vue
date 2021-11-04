<template>
  <div class="component">
    <Header />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Header } from '@/components/organisms';

export default defineComponent({
  components: {
    Header
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
