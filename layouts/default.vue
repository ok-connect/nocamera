<template>
  <div class="min-h-screen layout-grid">
    <TheHeader />
    <Nuxt />
    <TheFooter />
  </div>
</template>

<style scoped>
.layout-grid {
  display: grid;
  grid-template-rows: 80px auto 250px;
}
</style>
