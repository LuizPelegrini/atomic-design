<template>
  <div class="component">
    <Container>
      <Header />
    </Container>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

import { Container } from '@/components/bosons';
import { Header } from '@/components/organisms';

export default defineComponent({
  components: {
    Header,
    Container
  }
});
</script>

<style lang="scss" scoped>
.component {
}
</style>
