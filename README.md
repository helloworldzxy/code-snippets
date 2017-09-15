# ali-autumn/
demo-ES6.html和demo-prototype.html两个文件的html部分完全相同，js部分分别用ES6和`prototype`实现删除表的一行的功能。

无论哪种语法，都需要用箭头函数绑定`onclick`，以记录当前的`i` 。

无论哪种语法，用`getElementsByTagName("li")`都无法正确实现删除的效果，只能用
`querySelectorAll("li")`才能正确将`onclick`函数绑定到每个`li`元素上。可能与两种方法分别返回动态和静态的`NodeList`有关，但是具体原因尚未弄明白。