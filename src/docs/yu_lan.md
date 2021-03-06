# 预览

---

## 操作视频

<script src="//g.tbcdn.cn/tb/videocenter/1.2.4/js/tbvideo.js"></script>
<script id="tb_player">tb_player_object.embedPlayer({div:'tb_player',height:470,uid:62837672,vid:39414747,width:770},{autoplay:0},{})</script>

## 目录结构

以下是一个通过 `nowa init` 初始化的典型项目目录结构

```
.
├── abc.json  ------------------------- 项目构建配置文件
├── favicon.ico  ---------------------- 页面图标
├── html  ----------------------------- html目录
│   └── index.html  ------------------- 入口页面
├── package.json  --------------------- 项目配置
├── README.md  ------------------------ 说明文件
└── src  ------------------------------ 源码目录
    ├── app  -------------------------- 项目级代码
    │   ├── app.js  ------------------- 项目级脚本逻辑
    │   ├── app.less  ----------------- 全局样式
    ├── components  ------------------- 业务模块集合目录
    ├── i18n  ------------------------- 国际化文案资源文件
    │   ├── en.js
    │   ├── index.js  ----------------- 国际化资源加载器
    │   └── zh-cn.js
    ├── images  ----------------------- 图片资源目录
    └── pages  ------------------------ 页面集合目录
        └── demo  --------------------- 某一个页面
            ├── index.js  ------------- 页面入口文件
            ├── actions.js  ----------- 事件列表
            ├── store.js  ------------- 存储器
            ├── PageDemo.js  ---------- 页面视图逻辑
            └── PageDemo.less  -------- 页面样式
```

## 常用命令

- `nowa init` 

    代码生成（支持项目、页面、模块三种级别的代码生成，模板自动从云端同步）

- `nowa server`

    启动一个调式服务器（无刷新热替换、sourceMap、代理转发、变量注入、支持 https）

- `nowa build` 

    代码构建（通过目录约定支持多 entry、通过注入变量组合支持多端同时构建）

- `nowa lib` 

    UI 库构建（通过简单配置来构建第三方 UI 组件库，目前支持 [UXCore](http://uxco.re/)）
