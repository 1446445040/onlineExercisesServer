## 项目简述
服务器使用express框架搭建，主要用来为前端提供题目数据

运行服务，后台将遍历questions目录下存放的所有excel文件，并读取题库，等待客户端的查询。
题库文件只能为xlsxu文件，且题目必须符合一定的格式（题号，题目，四个选项，正确答案）。

在后端目录下cmd运行以下命令即可运行服务：
##### 安装依赖
```# npm install```
##### 运行服务
```# node index.js```