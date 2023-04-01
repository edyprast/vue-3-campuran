<template>
  <select @change="handleChange">
    <option value="">Please select your Coutry</option>
    <option value="US">United States</option>
    <option value="UK">United Kingdom</option>
    <option value="AU">Australia</option>
  </select>
</template>

<script>
export default {
  methods: {
    handleChange(event) {
      this.$emit('berubah', event.target.value.toUpperCase());
    },
  },
};
</script>
