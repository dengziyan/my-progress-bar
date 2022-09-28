# my-progress-bar

##效果如下：

![输入图片说明](https://gitee.com/deng_zi_yan/my-progress-bar/raw/main/progress.gif "在这里输入图片标题")

主要利用属性transition: width .5s;当改变width的大小时，就会产生过渡动画效果。

### 拓展：

animation和transition的区别及使用

1）transition 是过渡，是样式值的变化的过程，只有开始和结束；animation 其实也叫关键帧，通过和 keyframe 结合可以设置中间帧的一个状态；

2）animation 配合 @keyframe 可以不触发时间就触发这个过程，而 transition 需要通过 hover 或者 js 事件来配合触发；

3）animation 可以设置很多的属性，比如循环次数，动画结束的状态等等，transition 只能触发一次；

4）animation 可以结合 keyframe 设置每一帧，但是 transition 只有两帧；
