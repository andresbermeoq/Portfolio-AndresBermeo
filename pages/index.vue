<template>
  <main>
    <Navbar></Navbar>
    <h1>Hello World</h1>
    <NuxtLink to="/fun" no-prefetch>About page not pre-fetched</NuxtLink>
  </main>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "IndexPage",
});
</script>
