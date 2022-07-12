<script setup>
import Calculator from './components/Calculator.vue'
</script>

<template>
  <header>
    <h1 class="title">A really simple calculator made with Vue</h1>
  </header>

  <main>
    <Calculator />
  </main>
</template>

<style>
@import './assets/base.css';

.title {
  text-align: center;
  color: #fff;
  margin: 0;
  padding: 10vh 0 0 0;
}
</style>
