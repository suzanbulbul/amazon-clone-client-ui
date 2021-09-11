<template>
    <div>
        <app-navbar></app-navbar>
        <nuxt />
    </div>
  
</template>

<script>
import Navbar from '../../client/components/Navbar.vue'
export default {
    components: {
        appNavber: Navbar,

 
    },

}
</script>

<style>

</style>