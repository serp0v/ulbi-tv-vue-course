<template>
    <div>
        <h3 style="display: flex; justify-content: center;border: 1px solid black;padding: 5px;">Список постов</h3>
        <post-item
        v-for="post in posts"
        :key="post.id"
        :post="post"
        />
    </div>
</template>

<script>
import PostItem from './PostItem.vue'
export default {
  components: { PostItem },
    props: {
        posts:{
            type: Array,
            required: true,
        }
    }
}
</script>

<style>
    .post {
    padding: 15px;
    margin-top: 5px;
    border: 1px solid #000;
    }
</style>