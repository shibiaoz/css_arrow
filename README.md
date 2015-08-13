## 箭头实现原理

> 设置box的宽度和高度都为0， 设置border的值 ，上下左右，
  然后通过设置border-color来决定箭头的显示
  如果等腰三角形，那么border的各个方向的width保持，
  border 左右上线的宽度值不一样决定箭头的角度

> 箭头线是做的
    通过为元素，before after 来时实现两个三角形，两个三角形的color值不一样，用一个去覆盖另一个
    
> 具体实现看demo

可以实现 箭头，箭头线，提醒等

> 下一步，做个工具？ ==>  通过选择来实现各种效果，并产出源码


- [css arrow](http://ourjs.com/detail/532bc9f36922aa7e1d000001)
- [css3 filter 滤镜效果](http://html5-demos.appspot.com/static/css/filters/index.html)
- [css arrow ](http://cssarrowplease.com/)