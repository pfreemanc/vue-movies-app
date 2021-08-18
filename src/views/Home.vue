<template>
  <div class="home">
    <h1>Welcome to this movie thing. WIP. Obviously</h1>
    <router-link to="/search" class="button">Begin Whatever This Is</router-link>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  },
  data() {
    return {
      titleThing: process.env.VUE_APP_API_KEY,
    };
  },
};
</script>
