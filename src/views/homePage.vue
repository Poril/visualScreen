<template>
    <div class="main">
        <div class="container">
            <div class="header">
                <p class="headerTLeft">
                    <text class="textOne">20:08:46</text>
                    <text class="textTwo">2024/07/07 星期四</text>
                </p>
                <p class="headerTCenter">安全监管大屏</p>
            </div>
            <div class="middle">
                <div class="middleLeft">
                    <div class="mLeftOne">
                        <p class="mText">场所总览</p>
                        <img src="@/assets/safeImg/标题栏hdpi.png" class="mImg"> 
                        <ul class="mUl">
                            <li class="mLi">
                                <p class="mLTextOne">456</p>
                                <p class="mLTextTwo">机构总数</p>
                            </li>
                            <li class="mLi">
                                <p class="mLTextOne">456</p>
                                <p class="mLTextTwo">楼栋总数</p>
                            </li>
                            <li class="mLi">
                                <p class="mLTextOne">456</p>
                                <p class="mLTextTwo">厨房总数</p>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="middleCenter">中部内容</div>
                <div class="middleRight">右侧</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.main{
    background: #030d32;
    width: 1920px;
    height: 1080px;
    .container{  
        width: 1920px;
        height: 1080px;
        background-image: url('@/assets/bg/bghdpi.png'); /* 修改路径为相对于 CSS 文件的正确路径 */
        background-size: cover; /* 可以添加 background-size 属性来控制背景图的大小 */
        .header{
            width: 1920px;
            height: 120px;
            text-align: center;
            font-weight: bold;
            display: flex;
            .headerTCenter{
                width: 728px;
                line-height: 75px;
                font-family: 'STHupo', '华文琥珀', sans-serif;
                font-size: 38px;
                letter-spacing: 10px; 
                color: #adcdf6;
                margin: 0px;
            }
            .headerTLeft{
                    width: 598px;
                    font-size: 30px;
                    float: left;
                    .textOne{
                        color: #718fc6;
                        margin-right: 20px;
                    }
                    .textTwo{
                        font-size: 20px;
                        color: #4a649d;
                        margin-right: 118px;
                    }
            }
        }
        .middle{
            width: 1790px;
            height: 930px;
            display: flex;
            justify-content: space-between;
            color: #e5f1fc;
            margin: 0 auto;
            .middleLeft{
                width: 445px;
                .mLeftOne{
                    width: 445px;
                    height: 250px;
                    .mText{
                        margin: 0;
                        line-height: 0px;
                        font-size: 30px;
                    }
                    .mImg{
                        width: 445px;
                        margin-bottom: 10px;
                    }
                    .mUl{
                        width: 445px;
                        height: 160px;
                        list-style: none;
                        margin: 0;
                        padding: 0;
                        display: flex;
                        justify-content: space-between;
                        align-items: center;
                        text-align: center;
                        border: 1px solid #04285b;
                        box-shadow:inset 0 0 60px 15px rgba(4, 40, 91, 1);     /* 内部扩散 水平偏移量 垂直偏移量 模糊半径 扩散半径 色彩 */
                        .mLi{
                            margin: 0 20px 0 20px;
                            .mLTextOne{
                                color:#10c3cb;
                                font-size: 40px;
                                margin: 0;
                            }
                            .mLTextTwo{
                                margin: 10px 0 0 0 ;
                                font-size: 20px;
                            }
                        }
                    }
                }
            }
            .middleCenter{
                width: 850px;
                background: #131b2f;
            }
            .middleRight{
                width: 445px;
                background: #061e4d;
            }
        }
    }
}
</style>