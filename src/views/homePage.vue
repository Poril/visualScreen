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
                    font-size: 35px;
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
    }
}
</style>