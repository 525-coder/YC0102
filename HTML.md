 HTML

改变背景颜色：(从左到右渐变色)background: linear-gradient(to right , **color** ,**color** );

​						还有一种写法：background:linear-gradient(to right,rgb(  ,  ,  ),rgb(  ,  ,  ));

还原准则：从左往右，从上而下，从外往内。

实现盒子的圆角效果：border-radius:  px值。

调整盒子上面的距离：margin-top

调整盒子左边的距离：margin-left

调整字大小：font-size； 调整字的粗细：font-weight ；调整字的位置：text-align；

如果调整位置时，输入margin-top，页面没有任何反应，则说明出现了margin塌陷问题，解决此问题可以给外面的盒子加上padding-top和box-sizing:border-box同时出现，来解决问题

margin是用来加外边距的，padding是用来加内边距的，而盒模型的高度则是输入的高度加padding的高度，为了不改变盒模型实际大小，使用box-sizing进行限定。

想让两个东西横着排列，只需要增加属性：display：flex；

占位符 ： placeholder：

行高：line-heigt: 当行高设置成和盒子高度一致时，则文字居中

鼠标转换形态：cursor: pointer; 使文字不能被可选复制：user-select：none；

margin包含4个值，可以给两个也可以给四个

justify-content:space-between;'用于让框中的元素平分框中的空间；























