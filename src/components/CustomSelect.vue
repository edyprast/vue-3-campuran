<template>
  <select v-model="country">
    <option value="">Please select your Coutry</option>
    <option value="US">United States</option>
    <option value="UK">United Kingdom</option>
    <option value="AU">Australia</option>
  </select>
</template>

<script>
export default {
  props: ['name', 'lastName', 'alamat'],
};
</script>
