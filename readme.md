一起来cssup-_+
=========

[黑传说](http://jobinson.ga)常用的样式。

项目与众不同的地方：

- 高反馈设计：绝大部分元素都有反馈设定，可操作的反色，不可操作的变浅或变深。
- 更丰富的大小屏幕自适应设计
- 古文排版支持：左起竖写，大小屏幕古文排版自适应
- 去除不必要的渐变、阴影、圆角……使得性能更好。
- 强化针对左右撇子的内容展示和操作体验：分两套，一套适合左撇子，一套适合右撇子，默认适合右撇子。
- 注重内容：把屏幕主要部分给内容，尽可能少干扰内容的显示和使用。不建议安排占据版面的广告。
- 注重宽屏体验：不再顶部堆积太多元素，以免内容在屏幕过低的位置，内容展现不全，也会让人有压抑感，不能愉快地阅读。
- 注重眼睛健康：字体不小，颜色鲜明。


## 历史： ##

原版是[个人博客](http://jobinson.ga)断断续续几年手写的样式（那个年代苹果还没做手机），后来参考bootstrap，全面引入less来写，并根据自己的想法改造之，中间又引入了部分est的组件，最后参考zui，引入其中几个组件，并对组件结构进行大调整，引入其文档模式，基本成型。

感谢他们的辛勤努力。

- [twitter bootstrap](http://getbootstrap.com) 借鉴了其基础
- [百度 est](http://ecomfe.github.io/est) 借鉴了其内容特效
- [zui](http://zui.sexy) 借鉴了其文档和模块分类
- [淘宝支付宝AliceUI](http://aliceui.org) 借鉴了其流程部分设定
- [FontAwesome图标](http://) 全面引入图标
- [Animate.css动画](http://) 全面引入动画
- [百度echart.js](http://) 全面引入图表


换用 postcss来写？？？


## 规范 ##

命名方式：

- 界面效果使用前缀 ui
- 界面操控使用前缀 ctl

ui-大类名字-小类名字

- 加 ui 以方便区别 于其他类名（比如文档结构操作用的类名），方便监测。
- 使用横杆，方便输入

ctl-大类名字-小类名字

## 将做的事 ##

- [ ]加入大屏下拉动画
- [ ]幻灯改进
- [ ]触控支持
- [ ]动画按钮
- [ ]图表支持
- [ ]换用scss？？？？
- [ ]整理代码
- [ ]给每个自己的网站加皮肤
- [ ]文档页面自动生成


