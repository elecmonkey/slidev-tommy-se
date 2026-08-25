<template>
  <DotGrid />
</template>

<style>
.slidev-layout h1:not(.deck-title):not(.closing-title)::after {
  content: '';
  display: block;
  width: 3rem;
  height: 0.2rem;
  margin-top: 0.45rem;
  border-radius: 999px;
  background: var(--slidev-theme-primary);
  opacity: 0.55;
}
</style>
