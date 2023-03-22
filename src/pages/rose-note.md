# 项目结构
```
my-website
├── blog
│   ├── 2019-05-28-hola.md
│   ├── 2019-05-29-hello-world.md
│   └── 2020-05-30-welcome.md
├── docs
│   ├── doc1.md
│   ├── doc2.md
│   ├── doc3.md
│   └── mdx.md
├── src
│   ├── css
│   │   └── custom.css 全局css
│   └── pages
│       ├── styles.module.css
│       └── index.js
├── static
│   └── img
├── docusaurus.config.js
├── package.json
├── README.md
├── sidebars.js
└── yarn.lock

/blog/ - 包含博客的 Markdown 文件。如果你关闭了博客功能，则可以将此目录删除。你还可以通过设置 path 参数来改变此目录的名称。

/docs/ - 包含文档的 Markdown 文件。可在 sidebars.js 中自定义文档在侧边栏中的顺序。如果你关闭了文档功能，则可以删除该目录。你还可以通过设置 path 参数来改变此目录的名称。

/src/ - 非文档文件，例如独立页面（pages）或自定义的 React 组件。你不必严格地遵守将非文档文件放到这里，但是将它们集中在此目录下可以更轻松地进行管理，以便您需要进行某些格式校验或处理

/src/pages - 此目录中的任何扩展名为 JSX/TSX/MDX 文件都将被转换为网站的独立页面(page)。 

/static/ - 存放静态文件的目录。此处的所有内容都将被复制到最终的 build 目录的根目录下。

/docusaurus.config.js - 包含站点配置的配置文件。

/package.json - Docusaurus 网站也是一个 React 应用程序。你可以在其中安装和使用所需的任何 npm 软件包。

/sidebars.js - 生成文档时使用此文件来指定侧边栏中的文档顺序。
```

# 部署到github page
[参考资料](https://yingwinwin.github.io/blog/%E4%BD%BF%E7%94%A8docusaurus%E6%90%AD%E5%BB%BA%E5%8D%9A%E5%AE%A2%EF%BC%8C%E5%B9%B6%E9%83%A8%E7%BD%B2%E5%88%B0github%20pages/)