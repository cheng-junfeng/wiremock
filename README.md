# WireMock
- 模拟Http 后台服务请求

## 1 运行
- 双击start.bat (也可以直接双击startServer.vbs 隐藏cmd黑框)
- 运行此命令即可  端口8080

## 2 验证
- 浏览器输入
- http://127.0.0.1:8080/test   完成get 请求的测试验证，正常清空下，会显示
- {"code":1,"msg":"ok"}

## 3 说明
- _files 中存放upload 的文件
- mappings 中存放post/get 请求的响应匹配
