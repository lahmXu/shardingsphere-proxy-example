# shardingsphere-proxy-example

> 配置参考链接 https://shardingsphere.apache.org/document/current/cn/quick-start/shardingsphere-proxy-quick-start/

> 文件来源:
> 下载 shardingsphere 切换到 5.0.0-beta 版本
> 使用 mvn clean install -DskipTests -Dmaven.javadoc.skip=true -Drat.skip=true 打包,
> 然后在shardingsphere/shardingsphere-distribution/shardingsphere-proxy-distribution/target 目录下面会有个压缩包，这个包 gz 包就是 proxy 启动的程序了

操作说明:
1. 拷贝 mysql-connector-xxx.jar
2. 配置 server.yaml
3. 配置 config-xxx.yaml
4. sh bin/start.sh 启动
5. sh bin/stop.sh 停止