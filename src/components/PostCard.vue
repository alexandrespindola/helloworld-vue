<template>
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repudiandae iusto quis vero! Non, dolorem velit.</p>
        <PostButton />
    </div>
</template>

<script lang="ts" setup>
    import PostButton from './PostButton.vue';
</script>

<style scoped>
.post-card {
    background-color: #f2f2f2;
    padding: 20px;
    margin: 20px;
    border-radius: 15px;
    box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.1);
    max-width: 400px;
}   
</style>