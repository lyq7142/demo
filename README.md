# demo

ͼƬ����images�ļ����ȡ·����ʱ���� images/img.png      //imgҪ�滻
1.�ײ�����html����: 
   <!--�ײ�������-->
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

        <div class="text1">��ҳ</div>
        <div class="text2">��ͥΧ��</div>
        <div class="text3">����</div>
        <div class="text4">�ҵ�</div>

    </div>
2.������css���룺
/*�ײ�������*/

.footer{         
    width: 100%;
    height: 60px;
    background-color: #fff;
    z-index: 100;
    position: fixed;        /*�̶��ײ�������*/
    bottom: 0px;
    font-size: 13px;
    box-shadow: 0 -1px 5px 1px rgb(224, 222, 222);
    padding-top: 10px;
}
.tb1,.tb2,.tb3,.tb4,.text1,.text2,.text3,.text4{
    position: absolute;

}
/* ����ͼ�� λ�� */
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
/* ����������� λ�� */

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

�ƶ���������� ��
 <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">

����css���룺
<link rel="stylesheet" href="home.css">    //home Ҫ�滻
ͼƬ����Ӣ������


��ҳ index              .html      .css
��ͥΧ�� rail             .html      .css
���� community      .html      .css
�ҵ� my                   .html      .css
