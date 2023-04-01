<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />

    <input type="text" v-model="fname" />

    <p>Tampilan Input {{ fname }}</p>

    <GreetingMessage name="John" lastName="Doe" alamat="Surabaya" />
    <GreetingMessage :name="fname" :lastName="lname" :alamat="valamat" />

    <p>Country: {{ country }}</p>

    <CustomSelect />
  </div>
</template>

<script>
import GreetingMessage from './components/GreetingMessage.vue';
import CustomSelect from './components/CustomSelect.vue';

export default {
  name: 'App',
  components: {
    GreetingMessage,
    CustomSelect,
  },
  data() {
    return {
      fname: 'Edo',
      lname: 'Nebula',
      valamat: 'neptunus',
      name: '',
      country: '',
    };
  },
};
</script>
