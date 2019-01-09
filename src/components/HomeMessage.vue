<template>
  <div class="message">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default { name: 'HomeMessage', props: { msg: String } };
</script>
