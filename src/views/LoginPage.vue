<template>
  <Login />
</template>

<script>
import Login from '@/components/Login.vue'; // @ is an alias to /src
import Vue from 'vue'
export default Vue.extend({
  name: 'LoginPage',
  components: {
    Login,
  },
});
</script>

<style>

</style>