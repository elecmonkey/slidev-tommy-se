<template>
  <div class="dot-grid absolute inset-0 -z-1 pointer-events-none" />
</template>

<style scoped>
.dot-grid {
  background-color: #fbfdfe;
  background-image:
    radial-gradient(circle at 1px 1px, rgba(19, 172, 217, 0.28) 1px, transparent 0),
    radial-gradient(ellipse 70% 60% at 50% 40%, rgba(19, 172, 217, 0.1), transparent 70%);
  background-size: 22px 22px, 100% 100%;
}
</style>
