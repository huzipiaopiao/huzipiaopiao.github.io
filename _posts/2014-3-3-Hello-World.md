---
layout: post
title: 第一篇博客!
---

给大家推荐一个能让任何View，通过一行代码实现刮刮乐的库，[一行代码实现刮刮乐](https://github.com/huzipiaopiao/LuckyCardView).

<img src="https://github.com/huzipiaopiao/LuckyCardView/blob/master/img/demo.gif" width="30%" height="30%">

# 注意事项：
- 1、不要再调用view的`setOnTouchListener()`方法和`setForeground()`方法，否则会导致无法刮开；
- 2、当项目的minSdkVersion小于23时，view要是FrameLayout，其他类型的View会导致遮挡层无效，所以可以先在你xml布局中用FrameLayout包裹原view，再将FrameLayout传入helper中；
- 3、当项目的minSdkVersion大于等于23时，view可以是任何View；
