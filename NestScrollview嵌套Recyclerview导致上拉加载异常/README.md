NestScrollview嵌套Recyclerview会导致上拉加载异常,因为recyclerview会获取不到触摸事件,所以就会导致一直下拉加载,直至加载完所有数据.

解决方案:  1. 不用NestScrollview,然后把recyclerview上边的用addHead()方法,当做头布局放进去;recyclerview下边的当做footView放进去.

2.可以试试在整个布局,也就是NestScrollview外边包裹下拉刷新和上拉加载的布局.

