# Vite 基本实现原理

- Vite 是一个面向现代浏览器的，更轻、更快的 Web 应用开发工具
- Vite 基于 ES Modules 模块系统实现
- Vite 解决了 Webpack 冷启动时间过长，Webpack HRM 热更新反应慢的问题
- Vite 不需要打包，直接启动一个 Web 服务器，当发起请求时在服务端对请求的文件进行即时编译处理等操作