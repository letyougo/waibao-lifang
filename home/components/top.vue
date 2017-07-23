<template>
    <div class="top">
        <el-menu theme="dark" :default-active="activeIndex" class="el-menu-demo" mode="horizontal"
                 @select="handleSelect">
            <el-menu-item index="1">
               <a href="#">首页</a>
            </el-menu-item>
            <el-submenu index="2">
                <template slot="title">我的工作台</template>
                <el-menu-item index="2-1"><a href="#detail">房产再增值管理</a></el-menu-item>
                <el-menu-item index="2-2"><a href="#detail">房产安全保障</a></el-menu-item>
                <el-menu-item index="2-3"><a href="#detail">业务流程</a></el-menu-item>
            </el-submenu>
            <el-submenu index="3">
                <template slot="title"><a href="#detail">公司合作</a></template>
                <el-menu-item index="3-1"><a href="#detail">关于理房</a></el-menu-item>
                <el-menu-item index="3-2"><a href="#detail">房产安全保障</a></el-menu-item>

            </el-submenu>

            <el-submenu index="4">
                <template slot="title"><a href="#detail">新闻活动</a></template>
                <el-menu-item index="3-1"><a href="#detail">公司新闻</a></el-menu-item>
                <el-menu-item index="3-2"><a href="#detail">活动播报</a></el-menu-item>

            </el-submenu>

            <el-menu-item index="1">
                在线留言
            </el-menu-item>
            <!--<el-menu-item index="3"><a href="https://www.ele.me" target="_blank">订单管理</a></el-menu-item>-->
        </el-menu>


      







    </div>
</template>

<script>
    export default {
        name: 'top',
        data() {
            return {
                activeIndex: '1',
                activeIndex2: '1'
            };
        },
        methods: {
            handleSelect(key, keyPath) {
                console.log(key, keyPath);
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1, h2 {
        font-weight: normal;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    a {
        color: #42b983;
    }

    .top{
        min-width: 1280px;
    }

    .el-carousel__item h3 {
        color: #475669;
        font-size: 14px;
        opacity: 0.75;
        line-height: 200px;
        margin: 0;
    }

    .el-carousel__item:nth-child(2n) {
        background-color: #99a9bf;
    }

    .el-carousel__item:nth-child(2n+1) {
        background-color: #d3dce6;
    }
</style>
