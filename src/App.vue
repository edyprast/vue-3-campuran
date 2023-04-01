<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />

    <input type="text" />

    <GreetingMessage name="John" lastName="Doe" />
    <GreetingMessage name="John" lastName="Doe" />
    <GreetingMessage name="Eddy" lastName="Doe" />
  </div>
</template>

<script>
import GreetingMessage from './components/GreetingMessage.vue';

export default {
  name: 'App',
  components: {
    GreetingMessage,
  },
};
</script>
