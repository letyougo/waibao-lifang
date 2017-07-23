<template>
    <div class="content">

    
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


        <div class="content-outter content-item-1">
            <div class="content-inner">
                <el-row :gutter="20">
                    <el-col :span="18">
                        <el-row :gutter="20">
                            <el-col :span="12">
                                <el-card class="box-card"  :body-style="{ padding: '0px' }">
                                    <div slot="header" class="clearfix">
                                        <icon name="newspaper-o" class="card-icon" scale="1.5"></icon>
                                        <span style="line-height: 36px;">新闻-活动</span>
                                    </div>
                                    <img width="100%" height="100px" src="https://ss2.baidu.com/73Z1bjeh1BF3odCf/it/u=2674743804,2368804849&fm=202&gp=0.jpg&w_h=121_75&cs=2674743804,2368804849&ow_h=121_75&src=903"/>
                                    <div v-for="o in 4" :key="o" class="text item">
                                        <a href="#">新闻{{ o }}</a>
                                    </div>
                                    <a style="float: right" href="#">详细信息</a>
                                </el-card>
                            </el-col>

                            <el-col :span="12">
                                <el-card class="box-card" :body-style="{ padding: '0px' }">
                                    <div slot="header" class="clearfix">
                                        <icon name="info" class="card-icon" scale="1.5"></icon>
                                        <span style="line-height: 36px;">业务-理房创投</span>
                                    </div>
                                    <img width="100%" height="100px" src="https://ss2.baidu.com/73Z1bjeh1BF3odCf/it/u=2674743804,2368804849&fm=202&gp=0.jpg&w_h=121_75&cs=2674743804,2368804849&ow_h=121_75&src=903"/>

                                    <div v-for="o in 4" :key="o" class="text item">
                                        <a href="#">新闻{{o }}</a>
                                    </div>
                                    <a style="float: right" href="#">详细信息</a>
                                </el-card>
                            </el-col>
                        </el-row>
                        <br>
                        <el-row :gutter="20">
                            <el-col :span="12">
                                <el-card class="box-card" :body-style="{ padding: '0px' }">
                                    <div slot="header" class="clearfix">
                                        <icon name="thumbs-up" class="card-icon" scale="1.5"></icon>
                                        <span style="line-height: 36px;">联盟-合作</span>

                                    </div>
                                    <img width="100%" height="100px" src="https://ss2.baidu.com/73Z1bjeh1BF3odCf/it/u=2674743804,2368804849&fm=202&gp=0.jpg&w_h=121_75&cs=2674743804,2368804849&ow_h=121_75&src=903"/>

                                    <div v-for="o in 4" :key="o" class="text item">
                                        <a href="#">新闻{{o }}</a>
                                    </div>
                                    <a style="float: right" href="#">详细信息</a>
                                </el-card>
                            </el-col>

                            <el-col :span="12">
                                <el-card class="box-card" :body-style="{ padding: '0px' }">
                                    <div slot="header" class="clearfix">
                                        <icon name="star" class="card-icon" scale="1.5"></icon>
                                        <span style="line-height: 36px;">房产安全-业务流程</span>

                                    </div>
                                    <img width="100%" height="100px" src="https://ss2.baidu.com/73Z1bjeh1BF3odCf/it/u=2674743804,2368804849&fm=202&gp=0.jpg&w_h=121_75&cs=2674743804,2368804849&ow_h=121_75&src=903"/>

                                    <div v-for="o in 4" :key="o" class="text item">
                                        <a href="#">新闻{{o }}</a>
                                    </div>
                                    <a style="float: right" href="#">详细信息</a>
                                </el-card>
                            </el-col>
                        </el-row>

                    </el-col>
                    <el-col :span="6">
                        <el-card class="box-card" :body-style="{ padding: '0px' }">
                            <div slot="header" class="clearfix">
                                <icon name="newspaper-o" class="card-icon" scale="1.5"></icon>
                                <span style="line-height: 36px;">关于理房</span>

                            </div>
                            <img width="100%" height="100px" src="https://ss2.baidu.com/73Z1bjeh1BF3odCf/it/u=2674743804,2368804849&fm=202&gp=0.jpg&w_h=121_75&cs=2674743804,2368804849&ow_h=121_75&src=903"/>

                            <div v-for="o in 4" :key="o" class="text item">
                                <a href="#">新闻{{ o }}</a>
                            </div>
                            <a style="float: right" href="#">详细信息</a>
                        </el-card>
                        <br>
                        <el-card class="box-card" :body-style="{ padding: '0px' }">
                            <div slot="header" class="clearfix">
                                <icon name="newspaper-o" class="card-icon"  scale="1.5"></icon>
                                <span style="line-height: 36px;">广告位</span>

                            </div>
                            <img width="100%" height="100px" src="https://ss2.baidu.com/73Z1bjeh1BF3odCf/it/u=2674743804,2368804849&fm=202&gp=0.jpg&w_h=121_75&cs=2674743804,2368804849&ow_h=121_75&src=903"/>

                            <div v-for="o in 4" :key="o" class="text item">
                                <a href="#"> 新闻{{ o }}</a>
                            </div>
                            <a style="float: right" href="#">详细信息</a>
                        </el-card>
                    </el-col>
                </el-row>
            </div>
        </div>

        <br>

        <div class="content-outter content-item-2">
            <div class="content-inner">
                <el-card :body-style="{ padding: '0px' }">
                    <div slot="header" class="clearfix">
                        <icon name="user" scale="1.5"></icon>
                        <span style="line-height: 36px;text-align: center">房产在增值规划师</span>
                    </div>
                    <el-row :gutter="10">
                        <el-col :span="4" v-for="i in 6">
                            <el-card :body-style="{ padding: '0px' }">
                                <img width="100%" style="display: block" src="http://img1.imgtn.bdimg.com/it/u=1340226647,3141223728&fm=26&gp=0.jpg"></img>
                                <div class="des">
                                    <p>成立时间：2015-08-25</p>
                                    <p>服务：车贷/房贷/客户服务</p>
                                </div>
                            </el-card>
                        </el-col>
                    </el-row>
                </el-card>
            </div>
        </div>


        <br>

        <div class="content-outter content-item-3">
            <div class="content-inner">
                <el-card :body-style="{ padding: '0px' }">
                    <div slot="header" class="clearfix">
                        <icon name="flag" scale="1.5"></icon>
                        <span style="line-height: 36px;text-align: center">公司活动</span>
                    </div>
                    <el-row :gutter="10">
                        <el-col :span="4" v-for="i in 6">
                            <el-card :body-style="{ padding: '0px' }">
                                <img width="100%" style="display: block" src="https://ss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=3792736142,2365145464&fm=80&w=179&h=119&img.JPEG"></img>
                                <div class="des">
                                    <p>成立时间：2015-08-25</p>
                                    <p>服务：车贷/房贷/客户服务</p>
                                </div>
                            </el-card>
                        </el-col>
                    </el-row>
                </el-card>
            </div>
        </div>


        <br>

        <div class="content-outter content-item-4">
            <div class="content-inner">
                <el-card :body-style="{ padding: '0px' }">
                    <div slot="header" class="clearfix">
                        <icon name="user-o" scale="1.5"></icon>
                        <span style="line-height: 36px;text-align: center">客户风采</span>
                    </div>
                    <el-row :gutter="10">
                        <el-col :span="4" v-for="i in 6">
                            <el-card :body-style="{ padding: '0px' }">
                                <img width="100%" style="display: block" src="http://f10.baidu.com/it/u=41714617,1601911364&fm=72"></img>
                                <div class="des">
                                    <p>成立时间：2015-08-25</p>
                                    <p>服务：车贷/房贷/客户服务</p>
                                </div>
                            </el-card>
                        </el-col>
                    </el-row>
                </el-card>
            </div>
        </div>

    </div>
</template>
<script>
    export default{
        name:'content'
    }
</script>
<style scope>
    .content-outter{
        width: 100%;
        background: rgb(250,250,250);
    }
    .content-inner{
        width: 1280px;
        margin: 0 auto;
        background: rgb(255,255,255);
    }

    .box-card  a{
        text-decoration: none;
        color: #20a0ff;
        font-size: 14px;
        text-indent: 10px;
        display: block;
    }
    .box-card  a:hover{
        text-decoration: underline;
    }
    .clearfix *{
        vertical-align: middle;
    }

    .user-list,.user-item{
        height: 200px;
    }
    .user-item{
        float: left;
        width: 200px;
    }
    .card-icon{
        font-size: 16px;
    }
    .des p{
        line-height: 10px;
        font-size: 14px;
        text-indent: 10px;;
    }
</style>