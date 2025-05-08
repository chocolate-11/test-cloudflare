<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  {{ VERSION }}
</template>

<script setup>
import { VERSION } from "./config/url.js";
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
