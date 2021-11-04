<template>
  <div class="homepage">
    <DefaultTemplate>
      <template v-slot:header>
        <Header />
      </template>
      <template v-slot:content>
        <Presentation />
        <Services />
      </template>
    </DefaultTemplate>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import DefaultTemplate from '@/components/templates/DefaultTemplate.vue';
import { Header, Presentation, Services } from '@/components/organisms';

export default defineComponent({
  name: 'Homepage',

  components: {
    DefaultTemplate,
    Header,
    Presentation,
    Services
  }
});
</script>

<style lang="scss" scoped>
.homepage {
}
</style>
