<script setup lang="ts"></script>

<template>
  <div class="home">
    <h1>Home</h1>
    <p>Welcome to the home page!</p>
    <RouterLink :to="{ name: '/projects/[id]', params: { id: 1 } }">Go to Project 1</RouterLink>
  </div>
</template>
