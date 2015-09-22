<h1>天猫/地狗滚动导航实例总结</h1>
1.
<p>标准盒子模型边框包含padding和width，当width固定时，若改变padding则border大小跟随变化，width不变
。当width不固定而父元素有固定宽度时，改变padding，border大小不变
                #menu {
                position: fixed;
                top: 100px;
                left: 50%;
                margin-left: 400px;
                width: 50px;
                }//让menu紧挨居中元素右侧；
</p>
2.
<p>scrollTop:scrollTop() 方法返回或设置匹配元素的滚动条的垂直位置。

scroll top offset 指的是滚动条相对于其顶部的偏移。
语法:
        $(selector).scrollTop(offset)

如果该方法未设置参数，则返回以像素计的相对滚动条顶部的偏移。
</p>
3.<p>offset() 方法返回或设置匹配元素相对于文档的偏移（位置）。
语法
        $(selector).offset(function(index,oldoffset))
<table>
<tr>
<th>参数 </th><th>描述</th>
</tr>
<tr>
<td>value </td><td>必需。规定以像素计的 top 和 left 坐标.</td>
</tr>
</table>
可能的值：值对，比如 {top:100,left:0};
          带有 top 和 left 属性的对象.
</p>
4.
        $('a[href='+currentId+']')//注意写法

    

 
