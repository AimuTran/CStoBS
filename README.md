# CStoBS
## 本地WebSocket服务器实现与浏览器通信插件
此插件实现本地全局监听按键并通过websocket回传给浏览器客户端，实现BS与CS进行简单消息通信，基于此方案可以拓展其他功能插件。
### 插件功能
* 基于[SuperSocket](https://github.com/kerryjiang/SuperSocket), 可扩展的 Socket 服务器框架,实现本地WebSocket服务器
* 实现全局键盘监听
* 支持SSL
* 增加开机自启设置
* 支持XP及以上系统

由于项目需要，本人对C#语言不是很熟悉，代码也是边搜边写，部分代码不符合规范，请谅解。本插件提供一个实现BS到CS通信的方案思路，更多场景请拓展开发。