<script setup lang="ts">
import NavBar from "~/components/app/nav-bar.vue";

const authStore = useAuthStore();
authStore.init();
</script>

<template>
  <div class="flex min-h-screen flex-col">
    <nav>
      <NavBar />
    </nav>
    <main>
      <slot />
    </main>
  </div>
</template>
