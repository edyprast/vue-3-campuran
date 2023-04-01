<template>
  <p>Hello, {{ name }} {{ lastName }}!</p>
</template>

<script>
export default {
  props: ['name', 'lastName'],
};
</script>
