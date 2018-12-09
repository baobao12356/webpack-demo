# webpack-demo
记录自己学习webpack时练手的demo

## 项目运行
```
克隆仓库
git clone https://github.com/Lkkkkkkg/webpack-demo.git
进入相对应demo文件夹
cd demo01
安装依赖
npm install
启动(两种)
npm run build //demo01 - demo08 
npm run dev //demo09 - XX
```

demo01 - 初步安装webpack, 简单配置了webpack

demo02 - 对加载css进行了配置

demo03 - 对加载图片进行了配置

demo04 - 对加载字体进行了配置

demo05 - 对加载数据文件(JSON, XML, CSV等)进行了配置

demo06 - 配置了HtmlWebpackPlugin插件, 实现生成模板html, 自动引用出口文件

demo07 - 配置了CleanWebpackPlugin插件, 实现每次构建前dist文件夹的清理功能

demo08 - 使用了source map功能, 实现了跟踪源文件错误的功能

demo09 - 使用了webpack-dev-serve服务器, 实现了代码修改自动重载功能

demo10 - 使用了HMR(模块热替换)功能, 实现了修改模块不用重载功能

demo11 - 初步配置了react

demo12 - 初步配置了sass

demo13 - 使用了ExtractTextWebpackPlugin插件, 实现了把css独立分离到一个css文件夹里
