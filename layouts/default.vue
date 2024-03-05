<script lang="ts" setup>
import AppFooter from '~/components/AppFooter.vue';
import AppHeader from '~/components/AppHeader.vue';
</script>

<template>
  <div>
    <AppHeader />
    <main class="p-4 max-w-3xl mx-auto">
      <slot />
    </main>
    <AppFooter />
  </div>
</template>
