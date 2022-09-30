<template>
    <div
        class="post"
        v-for="post in posts">
            <div class="">Название <strong>{{post.title}}</strong></div>
            <div class="">Описание <strong>{{post.body}}</strong></div>
    </div>
</template>

<script>
export default {
    setup() {
        
    },
}
</script>

<style>
    .post {
    /* height: 300px;
    width: 300px; */
    /* display: flex; */
    padding: 15px;
    margin-top: 5px;
    border: 1px solid #000;
    /* flex-direction: column; */
    }
</style>