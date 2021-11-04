<template>
  <div class="social-networks">
    <SocialLink
      icon="github.svg"
      name="Github"
      to="https://github.com/LuizPelegrini"
    />
    <SocialLink icon="facebook.svg" name="Facebook" to="https://facebook.com" />
    <SocialLink icon="twitter.svg" name="Twitter" to="https://twitter.com" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { SocialLink } from '@/components/atoms';

export default defineComponent({
  components: {
    SocialLink
  }
});
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
