# 用法

代码示例

```
using socks5;

Socks5Server server = new Socks5Server(IPAddress.Any, 1080);
server.Start();
```

# 说明

1. 修复了 Socket.Receive 没有检查内容是否足够的问题

