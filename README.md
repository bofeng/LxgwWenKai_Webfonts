# LXGW WenKai / 霞鹜文楷 Web 字体

[![开源授权](https://img.shields.io/github/license/lxgw/LxgwWenKai)](https://github.com/lxgw/LxgwWenKai)

本仓库是 [霞鹜文楷](https://github.com/lxgw/LxgwWenKai/) 的 Web 字体，对中文字体进行分包和压缩，以便于用于网页端分发。

## 使用说明

**1. 引入 CSS 文件。** 可以按需只引入需要的。

在`@`后选择tag的版本号。这里使用的是`v1.310`，你可以查看当前repo的tags下都有哪些版本，然后直接替换。

```html
<!-- 霞鹜文楷 Regular -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/bofeng/LxgwWenKai_Webfonts@v1.310/dist/LXGWWenKai-Regular.css" />
<!-- 霞鹜文楷 Lite -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.310/dist/LXGWWenKai-Light.css" />
<!-- 霞鹜文楷 Bold -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.310/dist/LXGWWenKai-Bold.css" />
<!-- 霞鹜文楷 Mono Regular -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.310/dist/LXGWWenKaiMono-Regular.css" />
<!-- 霞鹜文楷 Mono Lite -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.310/dist/LXGWWenKaiMono-Light.css" />
<!-- 霞鹜文楷 Mono Bold -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.310/dist/LXGWWenKaiMono-Bold.css" />
```

**2. 应用字体样式。** 浏览器会根据所显示文字、粗细动态加载资源。

```css
/* 霞鹜文楷 */
body {
  font-family: LXGWWenKai sans-serif;
}

/* 霞鹜文楷 Mono */
pre, code {
  font-family: LXGWWenKaiMono monospace;
}
```

## How to build

1. Use `git` to clone this repo, fork it.
2. Delete all files under the `source` folder
3, Delete all files under the `dist` folder
4, Dopy your version of LXGW .ttf font files into the `source` folder.
5, Run `pnpm install` and `pnpm run build`. you will be able to see the generated files under the `dist` folder.


## Credits

1. 源字体预览，下载，尤其是授权信息，请务必查看源字体的github repo：[https://github.com/lxgw/LxgwWenKai](https://github.com/lxgw/LxgwWenKai)
1. 本repo fork自[https://github.com/satouriko/LxgwWenKai_Webfonts](https://github.com/satouriko/LxgwWenKai_Webfonts)