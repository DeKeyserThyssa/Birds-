<template>
  <div class="px-6 pt-3 pb-6">
    <footer class="mx-auto hidden max-w-6xl sm:block">
      <p class="text-sm text-neutral-800">
        Martijn Loth - Disclaimer {{ new Date().getFullYear() }}
      </p>
    </footer>

    <nav class="block sm:hidden">
      <AppNavigation />
    </nav>
  </div>
</template>

<script lang="ts">
import AppNavigation from './AppNavigation.vue'

export default {
  components: {
    AppNavigation,
  },
}
</script>
