## 我用了vscode自带的那个push git 办法，我不知道发成功没有

我去看一眼
命令行 git 套餐我常看常熟，半年学一次.....已经学到再也不想学的程度了。

vscode 办法：
- vscode 的逻辑是你打开project一定是打开的一个folder
- 所以这个folder就是你一键上仓的东西。
- 点击左边一列大icon的那个🔍下面，长得像分支的那个，就会问你：
- plan A是创建仓库（因为git是一种管理代码的工具，github不过是采用这个技术做得比较大的一家。）
- plan B 还是放到GitHub，我直接选这个，这个就是一个大button，点就行了。
- 然后就是打开浏览器，要授权，要设定一下是public还是private 
- 点完vscode就给你哗哗了放github仓库了，同名
- 然后要page 你就得去这个仓库的setting里搞githubpage 那一套，这个就是老生常谈了。
- 几分钟就完事。

### 要么animation我都先不管？

先不管, 能看就行
animation 通过切换classname来切换动画我写给你看

### intro 部分的swipe.js 的loop咋不起作用。

起了，script部分先把生成的slide放上面，再放swipe 的代码。

loop是无限循环的，估计是要去读总共的长度以及找下一张。
这个应该是动态的js完成的，只读了一次，因此无法获取到，就没法loop。

### timeline 还需要解决的问题
- 思路1: 搞个json格式，自己去读
涉及到的内容：js读json格式的处理
- 思路2: json长得很像object，所以可以现在script里塞个object写写看。
涉及到的内容：抽取数据，展示数据。
- 思路3 ：数据要放到合适的结构内，结构的样式也需要赋予class
涉及：JQ的比较烦的内容，比intro部分麻烦。Jq给我的观感就是缺很多个example 从易到难大合集，搞得人都不知道可以这样用。

JQ的网络资源是典型的滥用太多，不利于学习者。
官网那个也不是不行，就是感觉都在讲原理。


找到个教程：https://github.com/petersommerhoff/jquery-course 
看着还行，可以考虑看看。

- 思路4: animation是个问题
贸然引入了animate.js 是很好用，但是有没有用得很有水平，但是要是一直就在找js libraries，套js，天啊，难道就一直在干这种科学使用搜索引擎和test
.html的活吗.....

- 扩展
对animation.js 还是有兴趣，感觉和css的原生timeline（一个属性）结合一下可以做不少专题网页。
粗浅点说，这些效果不就是幻灯片切换和添加动画那个嘛..... 有了这个可以做网页版slide（虽然很多人做过还做很好还开源，啊这，别人写过我就不写了

翻了下svg animation，也比较有兴趣。

### 阶段感受

有些代码客观说得重写，幸亏是分了page写的part。
量少可以直接贴html，量多点就会变成考虑怎么js来写。

