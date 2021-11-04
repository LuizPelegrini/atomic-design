<template>
  <Container class="home-template">
    <slot name="header" />
    <slot name="content" />
  </Container>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Container } from '@/components/bosons';

export default defineComponent({
  name: 'DefaultTemplate',

  components: {
    Container
  }
});
</script>

<style lang="scss" scoped>
.home-template {
  margin: 5rem auto;
  display: grid;
  gap: 5rem;
}
</style>
