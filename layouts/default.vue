<template>
  <div id="app">
    <div id="nav">
      <Nav />
    </div>
    <nuxt />
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue";
export default {
  components: {
    Nav
  }
};
</script>
