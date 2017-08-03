# AndroidBottomNavigation
android底部导航
最近看到Android Studio里新建Activity时共选择模板中Bottom Navigation Activity可以实现Android底部导航的效果，在网上没啥参考资料，于是自己搞个教程方便大家学习指正哈。话不多说，直接效果图:（Android Studio：2.3.1）


https://github.com/yangyuscript/AndroidBottomNavigation/screenshot/S70803-095321.jpg
https://github.com/yangyuscript/AndroidBottomNavigation/screenshot/S70803-095326.jpg
https://github.com/yangyuscript/AndroidBottomNavigation/screenshot/S70803-095333.jpg
-----------------------------------
步骤：

1.新建Bottom Navigation Activity,包含layout文件activity_navigation.xml和class文件NavigationActivity：
（代码参考给出）

2.新建三个Fragment类：FragmentOne、FragmentTwo、FragmentThree和对应的三个layout文件：fragment_one.xml、fragment_two.xml、fragment_three.xml
（代码参考给出）

至此：一个简易的android底部导航功能就实现了，当然还有许多需要修改的地方，但整体的架构已经出来，希望大家能够参考指正，给我们一个新思路
