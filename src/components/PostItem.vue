<template>
    <div
    class="post">
    <div class="">
        <div class="">Название <strong>{{post.title}}</strong></div>
        <div class="">Описание <strong>{{post.body}}</strong></div>
    </div>
        <div class="post__btns">
            <my-button>Удалить</my-button>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        post: {
            type: Object,
            required: true
        }
    },
}
</script>

<style scoped>
.post {
padding: 15px;
margin-top: 5px;
border: 1px solid #000;
display: flex;
align-items: center;
justify-content: space-between;
}
</style>
//     v-for="post in posts"
//    :key="post.id"