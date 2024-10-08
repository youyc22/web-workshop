# HTML & CSS

​ HTML、CSS、JS 是网页三大语言，是网页的基础和本质。其中只需 HTML 和 CSS 文件就已经可以构建好看的静态网页了。我们在本节中将“画”出整个应用的首页、主页和“关于这个工程”页，并用简单的素材美化这些页面。在此过程中，我们希望同学们感受到“原来网页就是这么简单的东西”。

### 环境配置

- 一个正常运行的浏览器
- 了解`F12`开发人员工具的打开方式、元素页面和控制台的位置和查看方式

### 运行方式

双击打开`/frontend/public/index.html`，或右键使用浏览器打开。

若已提前安装了 NodeJS，可以使用 serve 包启动本地服务器，然后用浏览器访问`http://localhost:3000`

```bash
npm install -g serve
serve ./frontend/public
```

### 已实现的功能

| 哈希值前 7 位 | 提交信息                             | 对应知识点                   | 实现效果                                 |
| ------------- | ------------------------------------ | ---------------------------- | ---------------------------------------- |
| 199535c       | feat(01): a simplest page            | HTML 页面基本结构、语法      | 一个空白的首页                           |
| db8ebf5       | feat(01): basic HTML elements        | `<h1> <p> <a>`标签           | 首页上的文字                             |
| 9aeb5bf       | feat(01): more HTML elements         | 图片、音频、表格、列表、表单 | 主页和“关于这个工程”页的所有元素         |
| e1844cd       | feat(01): introduction to CSS        | CSS 的三种引入方式、基本语法 | 首页的背景图、文字位置、颜色             |
| e02b925       | feat(01): getting the right position | 盒子模型、定位方式           | 主页和“关于这个工程”页所有元素的相对位置 |
| e29fa24       | feat(01): different CSS selectors    | CSS 选择器、常用美化代码     | “关于这个工程”页的美化                   |

### 作业

新建一个“关于我”页面，可以从首页链接打开，页面上从多个方面（如爱好、趣事等）介绍你自己，要求使用至少 5 种 HTML 元素。

提示：任务可分解如下——

- 在首页添加链接
- 在`/frontend/public`内新建`about-me.html`，填充 HTML 页面基本结构
- 在`about-me.html`里添加所有你想展示的内容，选用合适的 HTML 元素呈现
- 使用 CSS 调整元素的相对位置、并调整颜色、形状使整体显示效果更美观
