<template>
  <div>
    <app-navbar></app-navbar>
    <app-logo></app-logo>
    <div></div>
    <nuxt-link to="/products" class="a-button-buy-again"
      >Add a new product</nuxt-link
    >
  </div>
</template>

<script>
import Logo from "../../client/components/Logo.vue";
import Navbar from "../../client/components/Navbar.vue";

export default {
  components: { 
    appLogo: Logo,
    appNavbar: Navbar 
    },
};
</script>
