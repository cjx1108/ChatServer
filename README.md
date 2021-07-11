# ChatServer
本项目开发环境为 Linux 下基于 Muduo 库建立服务器主框架， 采用 nginx 实现 tcp 负载均衡，基于mysql和 redis 发布-订阅的消息队列中间件，实现 用户登陆，注册，好友聊天，群聊等业务。采用 Cmake 构建自动化编译环境

编译方式
cd build
rm -rf*
cmake ..
make
