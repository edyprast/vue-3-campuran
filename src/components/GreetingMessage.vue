<template>
  <p>Hello, {{ name }} {{ lastName }} {{ alamat }}!</p>
</template>

<script>
export default {
  props: ['name', 'lastName', 'alamat'],
};
</script>
