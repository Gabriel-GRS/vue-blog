<template>
  <top-bar />
  <main class="h-auto bg-[#dde3e7] ">
    <div class="flex flex-col items-center gap-4 justify-center p-6">
      <span v-for="(post, index) in postsContent" :key="index">
        <PostCard :data="post.data" :text="post.text" :title="post.title" />
      </span>
    </div>
  </main>
</template>


<script setup lang="ts">
import TopBar from './global-components/top-bar.vue';
import PostCard from './components/PostCard.vue';
import postsContent from './utils/postsObject';

</script>