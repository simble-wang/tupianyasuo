# 图片压缩工具

这是一个简单易用的在线图片压缩工具，采用苹果风格设计，支持 PNG、JPG 等格式的图片压缩。

+ ## 在线演示
+ 
+ 访问 https://你的用户名.github.io/image-compressor 查看在线演示
+ 
+ ## 快速开始
+ 
+ 1. 克隆项目
+ ```bash
+ git clone https://github.com/你的用户名/image-compressor.git
+ ```
+ 
+ 2. 进入项目目录
+ ```bash
+ cd image-compressor
+ ```
+ 
+ 3. 使用任意 HTTP 服务器运行项目，例如使用 Python：
+ ```bash
+ # Python 3
+ python -m http.server 8080
+ # 或 Python 2
+ python -m SimpleHTTPServer 8080
+ ```
+ 
+ 4. 在浏览器中访问 `http://localhost:8080`

## 功能特点

- 支持拖拽上传或点击选择图片
- 支持 PNG、JPG 等常见图片格式
- 可调节压缩比例（1-100%）
- 实时预览压缩效果
- 显示压缩前后文件大小对比
- 支持压缩后图片下载
- 响应式设计，支持各种设备

## 技术实现

- 使用原生 HTML5 和 CSS3 技术
- 使用 FileReader API 读取图片
- 使用 Canvas API 进行图片压缩
- 使用 Flexbox 实现响应式布局
- 采用苹果风格设计语言 