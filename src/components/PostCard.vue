<template>
  <div class="card">
    <h2>
      <slot name="cardTitle">Fallback Title</slot>
    </h2>
    <slot>Fallback content</slot>
    <slot name="tombol">Fallback Title</slot>
  </div>
</template>

<script>
export default {
  props: ['content'],
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
