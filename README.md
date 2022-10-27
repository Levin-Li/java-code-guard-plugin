
[![](https://jitpack.io/v/Levin-Li/java-code-guard-plugin.svg)](https://jitpack.io/#Levin-Li/java-code-guard-plugin)

### 简介 
   
   Java代码保护插件(Maven)
 
### 1 集成
   
   在 pom.xml 文件加入一下配置

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
                <version>2.3.8</version>
                <executions>
                    <execution>
                        <id>encrypt-repackage</id>
                        <goals>
                            <goal>encrypt-repackage</goal>
                        </goals>
                    </execution>
                </executions>
            </plugin>
 
        </plugins>
    </build>
    
    </project>

 
### 2 联系作者

 邮箱：99668980@qq.com   
