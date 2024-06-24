<script setup>
  import PostButton from './PostButton.vue'
</script>

<template>
  <div class="post-card">
    <h3>Title</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur ultrices, est in luctus tincidunt, sapien eros consequat augue, id consequat sapien quam quis lorem.</p>
    <PostButton />
  </div>
</template>

<style scoped>
  .post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
  }
</style>