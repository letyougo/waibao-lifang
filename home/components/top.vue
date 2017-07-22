<template>
    <div class="top">
        <el-menu theme="dark" :default-active="activeIndex" class="el-menu-demo" mode="horizontal"
                 @select="handleSelect">
            <el-menu-item index="1">
                首页
            </el-menu-item>
            <el-submenu index="2">
                <template slot="title">我的工作台</template>
                <el-menu-item index="2-1">房产再增值管理</el-menu-item>
                <el-menu-item index="2-2">房产安全保障</el-menu-item>
                <el-menu-item index="2-3">业务流程</el-menu-item>
            </el-submenu>
            <el-submenu index="3">
                <template slot="title">公司合作</template>
                <el-menu-item index="3-1">关于理房</el-menu-item>
                <el-menu-item index="3-2">房产安全保障</el-menu-item>

            </el-submenu>

            <el-submenu index="4">
                <template slot="title">新闻活动</template>
                <el-menu-item index="3-1">公司新闻</el-menu-item>
                <el-menu-item index="3-2">活动播报</el-menu-item>

            </el-submenu>

            <el-menu-item index="1">
                在线留言
            </el-menu-item>
            <!--<el-menu-item index="3"><a href="https://www.ele.me" target="_blank">订单管理</a></el-menu-item>-->
        </el-menu>


        <el-carousel :interval="4000" type="card" height="400px">
            <el-carousel-item  :key="item">

                <img width="100%" height="100%" src="http://f11.baidu.com/it/u=3285610716,1088628422&fm=72"/>
            </el-carousel-item>

            <el-carousel-item  :key="item">

                <img width="100%" height="100%" src="http://f10.baidu.com/it/u=2942494105,612535989&fm=72"/>
            </el-carousel-item>

            <el-carousel-item  :key="item">

                <img width="100%" height="100%" src="http://img5.imgtn.bdimg.com/it/u=743447686,3607053305&fm=26&gp=0.jpg"/>
            </el-carousel-item>
        </el-carousel>








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
