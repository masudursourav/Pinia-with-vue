<script setup></script>

<template>
  <div class="counter">0</div>
  <div class="buttons">
    <button>-</button>
    <button>+</button>
  </div>
</template>

<style>
.counter {
  font-size: 4em;
  margin: 3rem;
}
.buttons {
  display: flex;
  justify-content: center;
  gap: 10px;
}
.buttons button {
  font-size: 2em;
  padding: 20px;
}
</style>
