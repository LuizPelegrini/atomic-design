<template>
  <div class="component">
    <Homepage />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

import Homepage from '@/components/pages/Home.vue';

export default defineComponent({
  components: {
    Homepage
  }
});
</script>

<style lang="scss" scoped>
.component {
}
</style>
