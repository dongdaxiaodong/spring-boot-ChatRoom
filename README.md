# spring-boot-ChatRoom
使用spring-boot集成的websockt完成的一个聊天室demo

这个demo是基于spring boot官网给出的websocket例子修改而成。

我在官方例子的基础上实现了局部广播

后端只改动了几行代码:将原来写死的路由添加上动态的部分，根据动态的部分来区分聊天室.

原来的例子:https://github.com/spring-guides/gs-messaging-stomp-websocket
