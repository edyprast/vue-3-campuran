<template>
  <PostCard>
    <template v-slot:cardTitle>Ini Gambar</template>
    <template v-slot:default>
      <img src="https://picsum.photos/200" />
    </template>
    <template v-slot:tombol> <button>Read more...</button></template>
  </PostCard>
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
