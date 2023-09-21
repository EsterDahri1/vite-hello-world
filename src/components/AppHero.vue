<script>
export default {
    name: 'AppHero',
    data() {
        return {
            jumbotronTitle: 'Jumbotron'
        };
    },
}
</script>

<template>
    <div class="jumbotron">
        <h3>{{ jumbotronTitle }}</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit autem nemo eligendi quasi iure fugiat, earum
            magni vero iste nesciunt nisi rerum debitis nam expedita natus quia officiis praesentium eius!</p>
        <a href="http://vitejs.dev">ViteJs</a>
    </div>
</template>

<style>
.jumbotron {
    width: 700px;
    height: 300px;
    border: 2px solid plum;
    border-radius: 1rem;
}
</style>