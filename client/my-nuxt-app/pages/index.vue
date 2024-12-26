<template>
  <div>
    <h1>Welcome to the Home Page</h1>
    <nuxt-link to="/about">Go to About</nuxt-link>
    <nuxt-link to="/film">Go to film</nuxt-link>
    <nuxt-link to="/ben">Go to ben</nuxt-link>
  </div>
</template>

<script lang="ts">
export default {
  name: 'HomePage',
}
</script>