## SpringBoot
-------------------

#### 下列哪个注解不能组成 @SpringBootApplication 注解？
- [x] `@PropertySource`
- [ ] `@Configuration`
- [ ] `@ComponentScan`
- [ ] `@EnableAutoConfiguration`

#### 下列关于 SpringBoot 中 YAML 格式配置的说法错误的是？
- [x] `支持 @PropertySource 注解导入自定义的 YAML 配置`
- [ ] `配置有序，在一些特殊的场景下，配置有序很关键`
- [ ] `支持数组`
- [ ] `简洁`

#### 在 SpringBoot 里面，哪种不能来加载配置？
- [ ] `properties 文件`
- [ ] `系统环境变量`
- [ ] `YAML 文件`
- [x] `全部都对`

#### 可以通过（）依赖，实现 SpringBoot 应用程序的安全性？
- [x] `spring-boot-starter-security`
- [ ] `mybatis-spring-boot-starter`
- [ ] `spring-boot-starter`
- [ ] `spring-boot-starter-data-jpa`

#### 下列关于 SpringBoot Batch 说法有误的是？
- [x] `在处理大量记录时非常重要，包括日志/跟踪，事务管理，作业处理统计信息，作业重新启动，跳过和资源管理`
- [ ] `通过优化和分区技术，可以实现极高批量和高性能批处理作业`
- [ ] `可以处理简单以及复杂的大批量批处理作业`
- [ ] `可以用于简化数据库访问`

#### 下列关于 SpringBoot 中 spring-boot-starter-actuator 特征说法正确的是？
- [ ] `使用 logback 进行日志记录`
- [ ] `选择特定嵌入式 Servlet 容器`
- [x] `使用一些如监控和跟踪应用的高级功能`
- [ ] `启用 Spring Framework 的缓存支持`

#### 默认 SpringBoot 打的是什么包？
- [x] `jar`
- [ ] `war`
- [ ] `普通文件夹`
- [ ] `zip`

#### 下列哪个注解不能绑定 SpringBoot 中的变量？
- [ ] `@ConfigurationProperties`
- [ ] `@Environment`
- [ ] `@PropertySource`
- [x] `@SpringBootApplication`

#### 下列哪个是 SpringBoot 的启动类注解？
- [x] `@SpringBootApplication`
- [ ] `@SpringBootConfiguration`
- [ ] `@Configuration`
- [ ] `@EnableAutoConfiguration`

#### 可以通过（）具，重新加载 SpringBoot 上的更改，而无需重新启动服务器？
- [ ] `git`
- [x] `DEV`
- [ ] `mave`
- [ ] `tomcat`

#### 下列哪个不属于 SpringBoot 优点的是？
- [ ] `功能强大，但是需要搜集复杂的 jar 包`
- [x] `代码量大，XML 配置多`
- [ ] `完全不需要配置 spring 和第三方库`
- [ ] `直接嵌入了 Tomcat 等服务器，无须部署 war 文件`

#### 由于 SpringCloud 和 SpringBoot 都发布了多个版本，选择这些版本时需要考虑兼容性。SpringCloud 的 Greenwich 版本与 SpringBoot 的哪个版本相匹配？
- [x] `SpringBoot 2.1`
- [ ] `SpringBoot 1.5`
- [ ] `SpringBoot 1.4`
- [ ] `SpringBoot 2.0`

#### 下列哪个是 SpringBoot 的全局配置文件？
- [x] `application.properties`
- [ ] `service.yml`
- [ ] `web.xml`
- [ ] `application.xml`

#### 以下依赖，导入的是什么包？
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>
```
- [ ] `spring-bootjdbc`
- [ ] `mavenC.spring-bootweb`
- [x] `spring-boot web`
- [ ] `spring-bootteSt`

#### 关于 SpringBoot 说法错误的？
- [ ] `SpringBoot 来简化 spring 应用开发，预定大于配置，justrun 就能创建一个独立的，产品级别的应用`
- [ ] `创建独立的 spring 引用程序 main 方法运行`
- [ ] `自动配置 spring 添加对应功能 starter 自动化配置`
- [x] `SpringBoot 用来替换 SpringMVC，约定大于配置`

#### 关于 Spring boot Actuator 功能说法错误的是？
- [ ] `在 pom.xml 文件中包含 spring-boot-starter-actuator 启动器`
- [x] `可以通过 spring-boot-starter-security 依赖集成到 Spring boot`
- [ ] `Spring boot Actuator 可以使用 HTTP 或 JMX 端点公开操作信息`
- [ ] `可以监控和管理 Spring boot 应用`

#### 下列哪个注解可以支持在 Spring boot 中实现定时任务功能？
- [ ] `@EnableAutoConfiguration`
- [ ] `@Configuration`
- [ ] `@ConditionalOnClass`
- [x] `@Scheduled`

#### 下列哪个不是 Spring boot 中 spring-boot-starter-parent 的作用？
- [ ] `执行打包操作的配置`
- [ ] `继承自 spring-boot-dependecies，写依赖时需要写版本号`
- [ ] `自动化的资源过滤`
- [x] `定义了 Java 编译版本为 1.8`

#### 下列关于 Spring boot actuator 说法有误的是？
- [x] `是 spring 启动框架中的重要功能之一`
- [ ] `可帮助访问生产环境中正在运行的应用程序的当前状态`
- [ ] `可直接作为 HTTP URL 访问的 REST 端点来检查状态`
- [ ] `默认情况下，所以敏感的 HTTP 端点都是不安全的`

#### Spring boot 如何兼容老 Spring 项目？
- [x] `使用 spring-boot-starter 依赖`
- [ ] `使用 @PropertySource 注解`
- [ ] `使用 @PropertySource 注解`
- [ ] `使用 @ImportResource 注解`