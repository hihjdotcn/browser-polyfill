对一些旧浏览器的渐进增强功能：
1. no-js  当浏览器未开启javascript时，我们为页面增加样式和html内容，以让访客看到我们在网页上放置的内容。
2. Modernizr 是一个 javascript 库，检查你的游览器是否支持 CSS3 或者 HTML5 的特性而自动添加一些类名（class）到 <html> 并 替换掉原来的 .no-js（简单来说，Modernizr 就是一个CSS3/HTML5 的测试器，你需要测试什么，这可以到它的官方网站配置，选择自己需要测试的元素）。