<script></script>

<template>
  <button class="btn"><slot /></button>
</template>

<style scoped>
.btn {
  font-family: var(--font-family);
  font-weight: 400;
  font-size: 24px;
  line-height: 150%;
  text-align: center;

  background: var(--color-button);
  color: var(--color-primary);
  border-radius: 100px;
  border: none;
  padding: 16px 10px;
  min-width: 335px;
  min-height: 68px;
}

.btn:hover {
  background: var(--color-button-hover);
}
</style>
