<template>
    <div class="index">
        <top></top>


        <bottom></bottom>
    </div>
</template>

<script>
    import bottom from '../components/bottom.vue'
    import top from '../components/top.vue'
    import middle from '../components/middle.vue'
    import float from '../components/float.vue'
    export default {
        name:'detail',
        components:{
            bottom,top
        }
    }
</script>