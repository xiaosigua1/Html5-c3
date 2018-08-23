盒子模型     div+css3


边框  border
border:1px  solid red;


border-color:边框颜色  上右下左四个边
border-top-color:上边框颜色
border-right-color:右边框颜色
border-bottom-color:下边框颜色
border-left-color:左边框颜色


border-width:边框粗细  上右下左四个边  thin  medium  thick 可以是像素
border-top-width
border-right-width
border-bottom-width
border-left-width

border-width:5px 10px ; 上下为5px  左右为10px
border-width:5px 10px  20px ;  上为5px  下为20px  左右为10px

border-style:边框样式
dashed  常用
solid   常用

none
hidden
dotted
double

简写：
border:1px  solid red; 规范写法
       粗细  样式  颜色！


margin:外边距
margin-top
margin-right
margin-bottom
margin-left

margin:5px 10px;上下外边距为5px  左右外边距为10px


margin:0px auto; 网页中的盒子居中显示！
前提：
  01.必须是块元素
  02.固定宽度


padding:内边距
padding-top
padding-right
padding-bottom
padding-left

padding:5px 10px;上下内边距为5px  左右内边距为10px

盒子模型总尺寸=内容宽度+padding+border+margin


box-sizing:设置盒子模型的大小规则

content-box:盒子的总尺寸
border-box:盒子的宽度或者高度 等于  内容的宽度或者高度
inherit:继承父盒子


圆角属性
border-radius:左上 右上  右下 左下

盒子阴影
 box-shadow:inset 10px 10px 1px pink;

inset:阴影类型   内 外
x轴
y轴
阴影半径
阴影颜色






