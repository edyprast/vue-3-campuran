<template>
  <div id="app">
    <PostCard content="Post Card 1" />
    <PostCard content="Post Card 2" />
  </div>
</template>

<script>
import Mix1 from './components/Mix1.vue';
import PostCard from './components/PostCard.vue';
export default {
  name: 'App',
  components: {
    Mix1,
    PostCard,
  },
};
</script>
