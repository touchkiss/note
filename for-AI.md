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

## [cliproxyapi 一个 OpenAI/Gemini/Claude/Codex 兼容的 API 服务](https://help.router-for.me/cn/)

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

## [rtk 高性能 CLI 代理，将 LLM token 消耗降低 60-90%](https://github.com/rtk-ai/rtk)


## [cc switch Claude Code、Codex、Gemini CLI、OpenCode 和 OpenClaw 的全方位管理工具](https://github.com/farion1231/cc-switch)

## [hermes 自进化 AI 代理](https://github.com/NousResearch/hermes-agent)

## claude code

在Terminal中运行claude，可以加--ide 连接到正在运行的vscode

## [rtk 用于压缩输入token](https://github.com/rtk-ai/rtk/blob/master/README_zh.md)

- 安装 brew install rtk
- 更新 brew upgrade rtk

## codex
- [cockpit tools可跳过chatgpt手机号验证](https://github.com/jlcodes99/cockpit-tools)