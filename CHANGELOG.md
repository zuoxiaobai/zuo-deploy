
# CHANGELOG

## 0.3.2
- fix:  修复 log \n 被忽略显示异常的问题，增加推荐的部署 shell 脚本内容
## 0.3.1 
- feat: 使用 prompt 将端口、密码改为询问方式输入
## 0.3.0
- feat: 使用 pm2 改造服务，防止 terminal 中断后进程被杀掉
## 0.2.2
- fix: npm 官网 github 链接更正
- fix: socket.io cdn 链接在服务器上运行时异常，将 cdn 替换为官方 cdn
## 0.2.0
- feat: 新增 socket 实时输出部署 log
- feat: 启动命令增加端口、密码参数配置
- feat: 引入session, 新增部署接口鉴权、前端登录功能 
- feat: 对页面 UI 进行简单修改, 优化提示, 提高 log 展示性能 
- feat: 部署 log 加时间戳
- chore: 去掉默认的 ES Module，使用默认的 CommonJS

## 0.1.4
- 初步完成自动化部署功能
- koa 提供自动化部署监听服务，请求接口服务，直接开始部署、执行shell脚本。部署完成后在前端页面显示部署 log
- 命令行工具支持 zuodeploy start 开启服务
