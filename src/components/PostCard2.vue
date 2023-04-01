<template>
  <div class="card">
    <slot name="title" :pTitle="postTitle">Hello</slot>
  </div>
</template>

<script>
export default {
  data() {
    return { postTitle: 'Post Title' };
  },
};
</script>

<style scope>
.card {
  max-width: 250px;
  text-align: center;
  margin: 2rem auto;
  padding: 0.6rem 0.8rem;
  border: 0.1rem solid #94a3b8;
  color: #64748b;
}
</style>
