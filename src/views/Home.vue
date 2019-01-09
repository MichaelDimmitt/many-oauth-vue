<template>
  <div class="home">
    <!--<img alt="Vue logo" src="../assets/logo.png">-->
    <HomeMessage msg="Cool, you must be logged in to the applications"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeMessage from '@/components/HomeMessage.vue';

export default {
  name: 'home',
  components: {
    HomeMessage,
  },
};
</script>
