## 导入项目

---

用户可以导入 nowa 项目和非 nowa 项目(即平时的项目)。

#### 导入方式

1、拖拽导入

直接把项目拖到工具里，工具会自动执行导入任务

2、在项目详情页点击 '文件夹' 按钮导入

<img src="sc_create_0.png" width="180">
<!--插图 -->

3、在欢迎页点击 '导入' 按钮导入

请戳[初始化](https://nowa-webpack.github.io/nowa/chu_shi_hua.html) 查看详情。

#### 导入后的安装

因为用户导入的项目五花八门，千奇百怪。所以特此加一道保险措施，即检查导入项目后检查用户是否把 'package.json' 里面的依赖安装了。

<img src="sc_create_1.png" width="800">

如果用户事前措施做的充分，已经执行了 `npm i`，那么直接可以一通到底。
如果否，请用户认真选择 npm 源后，and 静静等待安装进度走完后, 开启项目新人生。

<img src="sc_create_2.png" width="800">
<!--插图 -->

#### 不支持的项目

如果导入的文件夹里面不包含 'package.json'， 用户请不要恶意尝试了。


您觉得导入姿势不太对，请到[这里](https://github.com/nowa-webpack/nowa-gui/issues/new)提意见～

