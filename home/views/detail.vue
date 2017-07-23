<template>
    <div class="index">
        <top></top>
        <news></news>
        <float></float>
        <bottom></bottom>
    </div>
</template>

<script>
    import bottom from '../components/bottom.vue'
    import top from '../components/top.vue'
    import news from '../components/news.vue'
    import float from '../components/float.vue'
    export default {
        name:'detail',
        components:{
            bottom,top,news
        }
    }
</script>