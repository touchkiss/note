## antigravity

plugins:
- Antigravity Cockpit
- Claude Code for VS Code
- Alibaba Java Coding Guidelines
- IntelliJ IDEA Keybindings
- indent-rainbow
- Git Blame
- Extension Pack for Java Auto Config
- Extension Pack for Java
- Debugger for Java
- Language Support for Java(TM) by Red Hat
- Live Server
- Markdown All in One
- Markdown Preview Enhanced
- Maven for Java
- open in browser
- Project Manager for Java
- Rainbow CSV
- REST Client
- Spring Boot Dashboard
- Spring Boot Extension Pack
- Test Runner for Java
- Trailing Spaces

### 代理antigravity
- antigravity-tools
可通过brew安装

## openclaw

### 停止而不卸载
[launchctl unload ~/Library/LaunchAgents/com.clawdbot.gateway.plist](https://medium.com/@haseeb1431/how-to-stop-or-unistall-clawdbot-moltbot-f1a0e279716b)

## [cliproxyapi](https://help.router-for.me/cn/)

### 通过homebrew安装
```bash
brew install cliproxyapi
brew services start cliproxyapi
```

默认配置文件位于`/usr/local/etc/cliproxyapi/config.yaml`，可根据需要修改后，如修改remote-management.secret-key为自定义值,然后登录[http://localhost:8317/management](http://localhost:8317/management)使用该secret-key进行认证。
重启服务。
```bash
brew services restart cliproxyapi
```
然后在OAuth菜单中，添加codex、antigravity等的认证配置

然后在AI提供商菜单中，添加OpenAI、claude等的API配置，api-key等敏感信息可以在上面的config.yaml中查看和设置

