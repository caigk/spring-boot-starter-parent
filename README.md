# spring-boot-starter-parent

my spring-boot-starter-parent

## 内容

* java version 17
* spring boot starter version 2.6.6
* spring version 5.3.18
* spring boot version 2.6.6

## 技术参考

### java

* [java 17](https://docs.oracle.com/en/java/javase/17/)
* [java 17 doc](https://docs.oracle.com/en/java/javase/17/docs/api/index.html)
* [java formater](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Formatter.html)

* [lombok api](https://projectlombok.org/api/index.html)
* [POM Reference](https://maven.apache.org/pom.html)
* [swagger](https://swagger.io/)
* [vavr doc](https://docs.vavr.io/)
* [vavr api](https://www.javadoc.io/doc/io.vavr/vavr/latest/index.html)

* [swagger 官网：swagger.io](https://swagger.io/)
* [springfox 官网：springfox](http://springfox.github.io/springfox/)
* [springfox Github 仓库：springfox / springfox](https://github.com/springfox/springfox)
* [springfox-demos Github 仓库：springfox / springfox-demos](https://github.com/springfox/springfox-demos)
* [springfox Maven 仓库：Home » io.springfox](https://mvnrepository.com/artifact/io.springfox)

* [Externalized Configuration](https://docs.spring.io/spring-boot/docs/2.1.8.RELEASE/reference/html/boot-features-external-config.html)

* [OGNL](https://commons.apache.org/proper/commons-ognl/language-guide.html)

* [springdoc](https://springdoc.org/)

* [mybatis](https://mybatis.org/mybatis-3/zh/index.html)
* [mybatis-plus](https://www.mybatis-plus.com/)

* [Spring Framework Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/index.html)
* [Web on Servlet Stack](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html)
* [stomp](https://stomp.github.io/)
* [stomp spring](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#websocket-stomp)
  
* [logback configuration](https://logback.qos.ch/manual/configuration.html)

* [guava](https://guava.dev/)

### Centos 8

* [alibaba miror](https://developer.aliyun.com/mirror/centos?spm=a2c4g.11186623.0.0.57231f02cUPKsT)

### 测试相关

* [junit5](https://junit.org/junit5/)
* [mockito](https://site.mockito.org/)
* [assertj](https://assertj.github.io/doc/)
* [jmockdata](https://github.com/jsonzou/jmockdata)

### pdf

* [itext](https://itextpdf.com/)
* [jasperreport](https://community.jaspersoft.com/)
* [jfrog](https://jaspersoft.jfrog.io/ui/packages)
* [JasperReports 6.16 pdf 中文显示问题及解决方案](https://blog.csdn.net/antony1776/article/details/116534431)

## VSCode 配置

setting.json

```json

    "java.configuration.runtimes": [
        {
            "name": "JavaSE-1.8",
            "path": "/Library/Java/JavaVirtualMachines/jdk1.8.0_131.jdk/Contents/Home",
            "default": false
        },
        {
            "name": "JavaSE-11",
            "path": "/usr/local/opt/openjdk@11/libexec/openjdk.jdk/Contents/Home",
            "default": false
        },
        {
            "name": "JavaSE-17",
            "path": "/usr/local/opt/openjdk@17/libexec/openjdk.jdk/Contents/Home",
            "default": true
        }
    ],
```

```xml

    <properties>
        <!-- 为子项目提供公共配置 -->
        <java.version>17</java.version>
        <!-- 重要：会影响集成环境java版本 -->
        <maven.compiler.release>17</maven.compiler.release>
    </properties>

```
