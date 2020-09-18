## ✔️ 介绍

声明：本项目框架基于[vuepress-theme-resume](https://github.com/wannaxiao/vuepress-theme-resume)修改，高度复刻[resume](https://github.com/liweitianux/resume)的风格（为啥不用Latex？t~~exstudio安装包太大了懒得下~~）

**毕业/招聘季节，打铁除了自身硬，简历这个锤子柄好不好看舒不舒服也很重要**

1. 使用编辑器自带的 Markdown 预览。缺点：不够紧凑，格式可调性不高

2. 使用 Latex排版。缺点：学习成本略高（小小简历，杀鸡焉用牛刀🤪）

   效果如下：

<img src="https://pic.downk.cc/item/5f648a43160a154a6746ec4c.png" style="zoom:67%;" />

## 🚀 开始

### 环境要求

- git
- yarn/npm

### 方式一：直接开始

1.  第一步：git clone 或 download 该项目

2.  第二步：cd  My-Elegant-Resume

> 若环境中不存在 `yarn`/`npm`，则需要先[安装yarn](https://yarnpkg.com/zh-Hans/docs/install)

```bash
# 安装依赖包
yarn # 或 npm i

# 开始
yarn dev # 或 npm run dev
```

`yarn dev`运行完后，使用浏览器打开提供的网址

3.  第三步：修改 example/README.md，保存后网页将自动热更新

### ~~方式二：在vuepress中使用主题（不建议，也没必要）~~


## ❔常见问题

> 如何导出为 pdf?

使用`yarn dev`后，在浏览器中打开页面，然后按下CTRL+P，根据所写字数，调整页面比例至合适，即可导出为PDF

注意：打印-更多设置-取消勾选页眉和页脚。否则会有标题和日期。

> 如何控制导出的 pdf刚好只有 1 页？

~~方法一：.vuepress/styles/palette.styl 修改基准字体大小 $fontSize~~ <br>
方法二：chrome 打印 -> 更多设置 -> 缩放（**推荐**）

## 💡 重点

如果你有更好的想法，建议自己写。

如果它对你有所帮助，主动点 <b>⭐️<a href="#">Star</a></b> ~ （自觉点👀）

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018-present, PwnerZhang
