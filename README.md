
[![](https://jitpack.io/v/Levin-Li/java-code-guard-plugin.svg)](https://jitpack.io/#Levin-Li/java-code-guard-plugin)

### 简介 
   
   Java代码保护插件(Maven)
 
### 1 集成

#### 1.1 在 pom.xml 文件加入以下配置

    <repositories> 
        <repository>
            <id>jitpack.io</id>
            <url>https://jitpack.io</url>
        </repository> 
    </repositories>

    <pluginRepositories>
        <pluginRepository>
            <!--  插件库 -->
            <id>jitpack.io</id>
            <url>https://jitpack.io</url>
        </pluginRepository>
    </pluginRepositories>

    <build>
        <plugins>

            <plugin>
                <groupId>com.github.Levin-Li</groupId>
                <artifactId>java-code-guard-plugin</artifactId>
                <version>2.3.10</version>
            </plugin>
 
        </plugins>
    </build>
    
    </project>

#### 1.2 应用打包以后，手动执行插件的加密打包任务

### 2 联系作者

 邮箱：99668980@qq.com   
