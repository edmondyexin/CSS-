# 花里胡哨CSS
## 前言
记录一些自己碰到的喜欢的CSS样式和效果，希望有机会整合到自己的博客上面
### 简单玩具
#### 轮播图
基础版本（下面的绿色的背景颜色，我懒，懒得去掉）
![手风琴（简单）.gif](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/b3aabdabb4824e1aa076d3a8a9ed6891~tplv-k3u1fbpfcp-watermark.image?)

图片显示的对应内容放置在slide_show_basic 下

同时，我们增加一点小标题,作为装饰，文字和图片一样响应就可以了，比较简单。
 实现的话，内容比较简单，具体看代码即可。利用flex布局，将图片放到一行当中，然后对于书本悬浮的元素，使用伪类`:hover` 改变对应的图片占比大小即可

### 考察内容

* flex 或者float 等弹性布局
* 伪类`:hover` 
* 基础的`html`标签布局
* 了解`transition`属性 (可以自己尝试去掉，然后观察一样有什么不好的)

#### 任务

* 自己动手 仿照代码或者逻辑仿写

* 额外： 如果给图片增加一定的文字说明，如何让其与图片一起变化如下图

  

![slide_show_2](C:\Users\Edmond\Desktop\slide_show_2.gif)



玩转水滴

https://juejin.cn/post/7004496282907574279