第一种方法：就是和智控平台的应急详情里写的一样。

​	EmergencyDetailActivity中添加fragment，名字为ContainerFragment。

​	ContainerFragment布局使用自定义的MotionLayout，名字为SignleTouchMotionLayout，因为     MotionLayout是两段的，我们需要三段的。	

​	ContainerFragment布局文件的SignleTouchMotionLayout中添加标签layoutDescription和layout_collapseMode，layoutDescription设置xml文件bottom_scene，即约束规则。

​		    

第二种方法：使用material组件中的BottomSheet和BottomSheetBehavior组合使用。

地址：https://github.com/material-components/material-components-android