<template>
  <PostCard>
    <template v-slot:cardTitle>Ini Gambar</template>
    <template v-slot:default>
      <img src="https://picsum.photos/200" />
    </template>
    <template v-slot:tombol> <button>Read more...</button></template>
  </PostCard>

  <PostCard2>
    <template v-slot:title="p">{{ p.pTitle }}</template>
  </PostCard2>
</template>
<script>
import Mix1 from './components/Mix1.vue';
import PostCard from './components/PostCard.vue';
import PostCard2 from './components/PostCard2.vue';
export default {
  name: 'App',
  components: {
    Mix1,
    PostCard,
    PostCard2,
  },
};
</script>
