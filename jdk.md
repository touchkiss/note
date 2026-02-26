## 通过[sdkman](https://sdkman.io/jdks/)管理jdk

通过`curl -s "https://get.sdkman.io" | bash`安装sdkman
通常安装zulu-jdk8（oracle-jdk-1.8平替）、oracle-jdk-17、oracle-jdk-21（设为默认）、oracle-jdk-25（最新版本，测试用）

[运行以下命令将sdkman安装的jdk以软链接的方式添加到系统管理的jdk列表中](jdk-bash.sh)：

新装的jdk位于~/.sdkman/candidates/java目录下，打开 VSCode/trae/antigravity settings.json 的 terminal.integrated.profiles.osx: 更新 JDK 列表