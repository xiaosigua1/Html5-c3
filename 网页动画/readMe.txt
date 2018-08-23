css变形：transform
 平移   translate（x,y）
        translateX
        translateY
 transform:translate(100px,0)

 旋转   rotate(deg) 旋转多少度，不会改变元素的形状

 缩放   scale（x,y） 如果只书写了一个值，默认第2个参数等于第一个值
        scaleX
        scaleY

 倾斜   skew（x,y） deg 会改变元素的形状
        skewX
        skewY


 如果说我们想给一个元素同时设置多个 变形属性！
   transform： 倾斜  缩放  旋转  ；
    多个属性之间使用空格隔开！


我们上面的变形属性都是一瞬间就完成了！没有看到中间过程！

如果想看到！使用css过渡属性  transition==>是一个动画的转换过程！

css过渡属性：
transition:property  duration  timing-function  delay

property:过渡或者动画的css属性,例如color,width,如果想都设置使用all
duration:完成过渡效果需要的时间 s为单位
timing-function: 过渡函数
   ease：默认值  速度由快到慢
   linear：匀速
   ease-in:越来越快
   ease-out:越来越慢
   ease-in-out:先加速后减速
delay：过渡开始的延迟时间  s为单位


CSS动画

01.创建关键帧
@keyframes  名称(animates){
    0%{
      css属性：属性值；
    }
    50%{
      css属性：属性值；
    }
    100%{
      css属性：属性值；
    }
}
02.怎么调用关键帧
animation：关键帧的名称  3s linear 1s;


