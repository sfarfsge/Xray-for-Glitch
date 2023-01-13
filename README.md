## Glitch上部署vless
### 说明
只有该项目中的几个文件有用，其他Glitch自动生成的文件可以删掉，vless配置文件为config.json，可自定义修改，初始ws路径为/vless，UUID为 de04add9-5c68-8bab-950c-08cd5320df18 。貌似从github上导入需要很久而且不一定成功，建议直接创建`Hello Node`项目，然后再把该项目中的几个文件上传覆盖进去。
### 保活
`server.js`第93行替换成自己的url即可
### 查看状态
```
http://自己的url/status  # 查看进程
http://自己的url/vless  # 查看 vless 运行结果
```