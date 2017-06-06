## 网站性能优化项目

### 运行方式

通过 https://blastz.github.io/website_optimization/ 来访问这个网站

### 优化内容

**对 index.html 的优化**

 - 用 TinyPng 压缩了图片

 - 异步加载 analytics.js

 - 利用 webfontloader 异步加载 google font

 - 对 css 和 js 进行了压缩

 - 利用 media 优化阻塞渲染的 css

**对 pizza.html 的优化**

 - 使用 getElementById 和 getElementsByClassName 代替 querySelector

 - 使用 transform 代替 left

 - 使用 requestAnimationFrame 优化动画

 - 减少 pizza 的个数
