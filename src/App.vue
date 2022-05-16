<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <!-- <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header> -->
  <RouterView />
  <!-- <footer></footer> -->
</template>

<style>
@import "@/assets/base.css";

#app {
  min-height: 100vh;
  max-height: fit-content;
  width: 100vw;
}
</style>
