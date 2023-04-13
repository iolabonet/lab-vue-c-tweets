<template>
  <span class="user">
      <span class="name">{{ name }}</span>
      <span class="handle">@{{ handle }}</span>
    </span>
</template>

<script>
export default {
name: 'User',
  props: {
    name: String,
    handle: String,
  }
}
</script>

<style scoped>

</style>
