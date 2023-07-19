# 自建JRebel License Server
自建JRebel License Server 用到的源码（Java版）

编译打包：`mvn clean package`

启动服务：`java -jar JrebelLicenseServerforJava-1.0-SNAPSHOT-jar-with-dependencies.jar -p 8081`

JRebel激活窗口：
  * 访问地址：http://localhost:8081/{GUID}。
    可以直接复制服务启动时的日志中的地址。
    GUID可以使用UUID直接生成，或者使用https://www.uuidgenerator.net在线生成
  * 邮箱：填写任意邮箱即可。

注意事项：
* 激活时需要保持 `JrebelLicenseServerforJava` 服务启动着。
* 激活后需要将JRebel的工作模式修改为 `work offline`，180天内就不再需要激活了，可以关闭 `JrebelLicenseServerforJava` 服务。

# Fork源
👉[JrebelBrainsLicenseServerforJava](https://github.com/Dec12th/JrebelBrainsLicenseServerforJava)
