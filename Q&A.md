# Q&A

## 导出为 pdf 时报错

导出为 pdf 时报错：

`[ ERROR ] Failed converting Markdown. (Navigation timeout of 30000 ms exceeded)`

 `Failure to export: [CLIError] Failed converting Markdown. (Navigation timeout of 30000 ms exceeded)`

### 解决办法：

先导出为 html, 用 Chromium 内核的浏览器打开后, 按 `Ctrl+P` 打印, 打印机选择 "另存为 PDF", 如果页码很多打印过程会很慢.

打印后可能会很大, Acrobat 打开/加载可能会很慢, 可以通过 Acrobat 内工具中的 "优化 PDF" -> "减少文件大小", 经过漫长的等待后可以优化打开/加载速度.
