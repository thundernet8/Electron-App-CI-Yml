## Electron-App-CI-Yml
Travis&amp;Appveyor CI configurations for Electron App building and release to Github

为你的Electron应用添加持续集成服务Travis和Appveyor的配置文件

Travis - 用于自动构建并发布MacOS、Linux版的应用
Appveyor - 用于自动构建并发布Windows版的应用

## 注意
你还需要至Travis和Appveyor网站，配置你的Project的环境变量，添加下面一条记录:

```
变量名: GH_TOKEN
变量值: 去github个人设置中添加一个access token, 权限可勾选public repos
```