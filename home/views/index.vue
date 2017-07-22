<template>
    <div class="index">
        <top></top>
        <middle></middle>
        <float></float>
        <bottom></bottom>
    </div>
</template>

<script>
    import bottom from '../components/bottom.vue'
    import top from '../components/float.vue'
    import middle from '../components/middle.vue'
    import float from '../components/float.vue'
    export default {
        name:'index',
        components:{
            bottom,top,middle,float
        }
    }
</script>