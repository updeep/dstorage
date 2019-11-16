# description

## directory name rule
```
example：dist.20191016.01
explain：dist.currDate.vNum
```

## dist structure

key|desc
---|---
 / |
	├─ app/             | 程序内部资源，包含配置文件、GUI图片、帮助文档
	├─ bin/             | 启动脚本，Linux/Windows的打开方式
	├─ libs/            | 外部引用资源（maven打包后生成的jar包）
	├─ logs/            | 日志文件夹
	├─ webapp/          | 页面静态资源，包含文件上传本地存储files文件夹
	├─ file-service.jar | 程序jar包

## open mode
- Linux
`
sh bin/startup.sh
`
- Windows
`
double click on bin/startup.bat
`