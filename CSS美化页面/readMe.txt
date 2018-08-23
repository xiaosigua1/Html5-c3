css美化页面

如果在我们一行文字中，想让某个文字凸显出来，使用span！

1.字体样式
   font-style:字体的风格   italic  normal
   font-weight:字体的粗细   normal(默认400) bold(700)  bolder  最大到900
   font-size:字体的大小   10px  2em   rem  pc  pt
   font-family:字体的类型，比如我们的楷体，隶书,宋体。。。。。

   font：风格 粗细 大小 类型
    在一起设置属性的时候，四种属性顺序不能颠倒！

2.文本样式
       color:文本颜色 red  16进制颜色码  rgb   rgba
             rgb(red,green,blue)正数取值 0-255
             rgba(red,green,blue,alpha)
             alpha的取值必须是0-1  0不显示  1正常显示
  text-align:文本元素的水平对齐方式
            center  left  right  justify(两端对齐)
  line-height:文本的行高!
       如果想设置文本的垂直居中line-height的值必须等于height的值
  text-indent:设置首行缩进
                 p{
                  text-indent:2em; 设置p首行缩进2个字符
                   }
  text-decoration:文本的装饰
           none:默认值
      underline:下划线
       overline:上划线
   line-through:删除线
    text-shadow:文本阴影

3.display  可以实现 块元素和行内元素的互换！
   inline inline-block  block

4.超链接伪类

   结构伪类选择器：
      div:nth-of-type()  :nth-child
   css伪类是一个特殊的类！ 它针对于我们设置的css选择器起作用！

   css伪类的语法：
       选择器:伪类名｛
                     属性:属性值;
                     ｝
  :link     ==> 还没有点击超链接的样式
  :visited  ==> 点击之后超链接的样式
  :hover    ==> 鼠标悬停在超链接的样式
  :active   ==> 鼠标点击未释放超链接的样式

 love  hate
 如果同时给一个选择器设置超链接伪类样式，那么顺序是必须不变的！

5.列表样式
  list-style-type   列表符号样式
      none    无符号
      disc    实心圆
      circle  空心圆
      decimal 数字  .....
  list-style-image  列表图片  url
  list-style-position 列表符号是否被li包含，默认是ul包含
  list-style        列表样式

如果同时设置了type和image  那么image会覆盖type！和书写先后顺序没关系！

6.背景样式
    background-color:背景色
    background-image:背景图片
    background-position:背景位置
    background-repeat:背景重复方式
        repeat:默认方式 水平和垂直都平铺
        no-repeat:不平铺，只有一个图片
        repeat-x:水平平铺
        repeat-y:垂直平铺

    background: 背景色 背景图片 背景位置  平铺方式
    虽然没有固定顺序，但是我们有个默认的写法！

如果我们相对背景图片的大小进行设置！那么请使用background-size
background-size:contain;
           background-size：背景图片的尺寸
            auto:默认值，使用图片的大小
            cover:让整个图片正好填充整个盒子
            contain：让图片自动的方法或者缩小 适应盒子的大小
            percentage：使用百分比  手动的校正图片在盒子中的大小


7.渐变属性
  linear-gradient:(方向,color1,color2)
                to top :方向
                red:第1个颜色
                black:第2个颜色
IE浏览器是Trident内核，加前缀：-ms-
Chrome浏览器是Webkit内核，加前缀：-webkit-
Safari浏览器是Webkit内核，加前缀：-webkit-
Opera浏览器是Blink内核，加前缀：-o-
Firefox浏览器是Mozilla内核，加前缀：-moz-
