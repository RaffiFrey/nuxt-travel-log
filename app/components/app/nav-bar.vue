<script setup lang="ts">
import ThemeToggle from "~/components/app/theme-toggle.vue";
import AuthButton from "~/components/auth-button.vue";
</script>

<template>
  <div class="navbar bg-primary text-primary-content">
    <div class="navbar-start">
      <NuxtLink to="/" class="btn btn-ghost text-xl">
        Travel Log
      </NuxtLink>
    </div>
    <div class="navbar-end">
      <ThemeToggle />
      <AuthButton />
    </div>
  </div>
</template>
