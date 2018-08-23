网页会根据块元素或者内联元素的特性，按照从左至右，从上到下的方式自然排序！
        这种元素自然排列的方式，我们称之为====》标准文档流！

浮动 float
  左浮动
  右浮动
浮动之后 会脱离 标准文档流

溢出 overflow
 overflow:
             01.visible:默认显示
             02.scroll：以滚动条的形式显示溢出部分
             03.hidden：溢出部分隐藏
             04.auto：自动跳转

 我们书写了一个页面，里面有很多块元素，默认排版就是标准文档流！

 如果我们想让ul中的li能在一行显示！
 01.display
 02.浮动

 只要是元素设置了浮动就会脱离标准文档流!
 如果我们的父元素容不下浮动元素！
 可以选择是否显示溢出的元素！
 使用overflow!

clear  清除浮动
  none  默认
  left  在左侧不允许浮动
  right 在右侧不允许浮动
  both  左右侧都不允许浮动



防止父级边框塌陷的方式：
01.给父级盒子设置宽高！
02.在父级盒子的最后一个位置增加div没有内容
<div  class="clear"></div>
 给这个div增加样式
     .clear{
               border: 1px solid black;
               clear: both;
           }
03.在父盒子中设置溢出处理
 overflow: hidden;
04.最终使用的方式  :after伪类
   在父盒子中增加一个class="clear"
   .clear:after{
              display: block;/*在#main div的左后一个位置增加一个块元素*/
              content: '';   /*块元素的内容什么都没有*/
              clear: both;  /*清除浮动*/
          }




