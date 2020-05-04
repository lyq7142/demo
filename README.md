# demo

图片放在images文件夹里，取路径的时候用 images/img.png      //img要替换
1.底部导航html代码: 
   <!--底部导航栏-->
    <div class="footer">
        <div class="tb1">
            <a href="#"><img src="images/tb1_green.png" width="30px" /></a>
        </div>
        <div class="tb2">
            <a href="#"><img src="images/tb2.png" width="30px" /></a>
        </div>
        <div class="tb3">
           <a href="#"><img src="images/tb3.png" width="30px" height="28px" /></a>
       </div>
        <div class="tb4">
            <a href="#"><img src="images/tb4.png" width="32px" /></a>
        </div>

        <div class="text1">首页</div>
        <div class="text2">家庭围栏</div>
        <div class="text3">社区</div>
        <div class="text4">我的</div>

    </div>
2.导航栏css代码：
/*底部导航栏*/

.footer{         
    width: 100%;
    height: 60px;
    background-color: #fff;
    z-index: 100;
    position: fixed;        /*固定底部导航栏*/
    bottom: 0px;
    font-size: 13px;
    box-shadow: 0 -1px 5px 1px rgb(224, 222, 222);
    padding-top: 10px;
}
.tb1,.tb2,.tb3,.tb4,.text1,.text2,.text3,.text4{
    position: absolute;

}
/* 导航图标 位置 */
.tb1{
    left: 6%;
}
.tb2{
    left: 32%;
}
.tb3{
    right: 31%;
}
.tb4{
    right: 6%;
}
/* 导航里的文字 位置 */

.text1,.text2,.text3,.text4{
    bottom: 10px;
    color: rgb(168, 167, 167);
    
}
.text1{
    left: 7%;
}
.text2{
    left: 30%;
}
.text3{
    right: 31%;
}
.text4{
    right: 7%;
}

移动端适配代码 ：
 <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">

调用css代码：
<link rel="stylesheet" href="home.css">    //home 要替换
图片尽量英文命名


首页 home               .html      .css
家庭围栏 rail             .html      .css
社区 community      .html      .css
我的 my                   .html      .css
