<template lang="html">
  <div class="notification is-danger">
    {{ message }}
  </div>
</template>

<script>
  export default {
    name: 'Notification',
    props: ['message']
  }
</script>

<style lang="css">
</style>
