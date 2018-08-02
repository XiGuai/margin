*css三大重点：css盒子模型、浮动、定位
*盒子模型有元素的内容、边框（border）、内边距（padding）、和外边距（margin）组成。
1、*盒子边框：
- 边框的样式：
- none：没有边框即忽略所有边框的宽度（默认值）
- solid：边框为单实线(最为常用的)
- dashed：边框为虚线  
- dotted：边框为点线
*合并单元格边框： border-collapse: collapse; 
2、内边距padding:
当盒子有宽度时：设置padding 盒子会被撑大；如果没有给一个盒子设置宽度，则padding不会撑开盒子，不会影响盒子大小。（padding: 10px 20px 27px;上10 左20 下27 右和对边取值相同）内容和边框有了距离。
3、外边距margin:(对行内元素只能设置左右边距，不能设置上下边距)
4、让块级盒子水平居中对齐margin:
（1）盒子必须有宽度（2）必须是块级元素（3）左右外边距设置为auto（margin-left: auto; margin-right: auto;或 margin: auto;或margin: 0 auto;);
5、文字居中和盒子居中区别:（1） 盒子内的文字水平居中是  text-align: center,  而且还可以让行内元素和行内块居中对齐;（2）块级盒子水平居中  左右margin 改为 auto 
*text-align: center;行内元素 行内块元素水平居中 */
*margin: 10px auto;  /* 块级盒子水平居中  左右margin 改为 auto */


*css3：盒子圆角边框;
border-radius: length;(50%正圆；)
*css3:盒子阴影：
box-shadow:水平阴影 垂直阴影 模糊距离（虚实）  阴影尺寸（影子大小）  阴影颜色  内/外阴影；
