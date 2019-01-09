<template>
  <div class="meetup-auth">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'MeetupAuth',
  props: {
    msg: String,
  },
};
</script>
