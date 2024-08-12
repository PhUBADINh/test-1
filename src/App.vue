<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <div class="header">
    <ul>
      <li>
        <router-link to="/">Home</router-link>
      </li>
      <li>
        <router-link to="/about">About</router-link>
      </li>
      <li>
        <router-link to="/contectus">contectus</router-link>
      </li>
    </ul>
    <h1>Hello</h1>
  </div>
  <RouterView />
</template>

<style scoped>
ul{
  margin: 0;
  padding: 0;
}
li{
  display: inline;
  margin-right: 10px;
}
</style>
