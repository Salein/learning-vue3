<script setup>
import WelcomeItem from './WelcomeItem.vue'
</script>

<template>
  <WelcomeItem>

    <template #heading>Documentation</template>


  </WelcomeItem>

  <WelcomeItem>

    <template #heading>Tooling</template>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

  </WelcomeItem>
</template>
