## Spring MVC
-------------------

#### 下面关于组合注解的说法正确的是？
- [ ] `@GetMapping 注解可以用来匹配 GET 和 POST 方式的请求`
- [ ] `在所有的 Spring 项目中，使用组合注解可以替代 @RequestMapping 注解`
- [ ] `组合注解可以简化常用的 HTTP 方法的映射`
- [ ] `组合注解是 Spring3.x 版本中的新特性`

#### 下列选择中，不属于 SSM 整合时所需的 JAR 包的是？
- [ ] `spring-web-4.3.6.RELEASE.jar`
- [ ] `xwork-core-2.3.24.jar`
- [ ] `spring-webmvc-4.3.6.RELEASE.jar`
- [ ] `ant-1.9.6.jar`

#### 用户通过浏览器向服务器发送请求时，负责拦截用户请求的是？
- [ ] `处理器映射器`
- [ ] `前端控制器`
- [ ] `处理器`
- [ ] `处理器适配器`

#### 下面关于 Spring MVC 特点说法错误的是？
- [ ] `支持国际化`
- [ ] `使用基于 XML 的配置文件，在编辑后，不需要重新编译应用程序`
- [ ] `可自动绑定用户输入，并能正确的转换数据类型`
- [ ] `灵活性强，但不易于与其他框架集成`

#### Spring MVC 入门程序中，不是必须引入的 JAR 包是？
- [ ] `spring-web 和 spring-webmvc 的 JAR 包`
- [ ] `commons-logging 的 JAR 包`
- [ ] `Spring 的 4 个核心 JAR 包`
- [ ] `log4j 的 JAR`

#### Spring MVC 中的拦截器（Interceptor）类似于 Servlet 中的（），它主要用于拦截用户请求并作相应的处理？
- [ ] `HandlerAdapter`
- [ ] `ViewResolver`
- [ ] `handle`
- [ ] `过滤器或 Filter`

#### Spring MVC 支持多种视图技术，不包括哪个？
- [ ] `Velocity`
- [ ] `xml`
- [ ] `FreeMarker`
- [ ] `JSP`

#### 下面关于包装 POJO 类型数据绑定的说法正确的是？
- [ ] `如果查询条件参数是包装类中 POJO 的子属性，则参数名必须为属性名`
- [ ] `如果查询条件参数是包装类的直接基本属性，则参数名必须使用对应的"对象.属性名"`
- [ ] `如果查询条件参数是包装类的直接基本属性，则参数名直接用对应的属性名`
- [ ] `如果查询条件参数是包装类中 POJO 的子属性，则参数名必须为"对象.子属性.属性值"的形式`

#### 使用包装 POJO 类型数据绑定时，如果前端条件参数是包装类中 POJO 的子属性，则参数名必须为？
- [ ] `属性`
- [ ] `对象.属性`
- [ ] `对象`
- [ ] `全部不对`

#### JSON 对象的数组结构以"\["开始，以"\]"结束，中间部分由（）以英文","分隔的值的列表组成？
- [ ] `1`
- [ ] `2`
- [ ] `0 个或多个`
- [ ] `0`

#### RequestMapping 注解类型用于映射？
- [ ] `一个类`
- [ ] `一个对象`
- [ ] `一个请求或一个方法`
- [ ] `一个接口`

#### 下面不属于拦截器类中的方法的是？
- [ ] `afterpletion()`
- [ ] `afterCompletion()`
- [ ] `preHandler()`
- [ ] `postHandle()`

#### 下面关于 SSM 框架的整合说法错误的是？
- [ ] `SSM 框架的整合就涉及到 Spring 与 MyBatis 的整合`
- [ ] `SSM 框架的整合就涉及到 Spring MVC 与 MyBatis 的整合`
- [ ] `Spring MVC 与 Spring 之间不存在整合的问题`
- [ ] `SSM 框架的整合就涉及到 Spring MVC 与 Spring 之间的整合`

#### 在视图解析器配置中，可以设置视图的是？
- [ ] `处理器`
- [ ] `前缀和后缀`
- [ ] `适配器`
- [ ] `映射器`

#### 以下有关 Spring MVC 配置文件中拦截器的配置说法错误的是？
- [ ] `<mvc:exclude-mappng> 元素用于配置不需要拦截的路径请求`
- [ ] `<mvc:interceptors> 元素用于配置一组拦截器，其子元素 <bean> 中定义的是指定路径的拦截器`
- [ ] `<mvc:interceptors> 元素中可以同时配置多个 <mvc:interceptor> 子元素`
- [ ] `要使用 Spring MVC 中拦截器，要先自定义拦截器还需要在配置文件中进行配置`

#### 下列选项中，属于 Spring MVC 所必须的 JAR 包的是？
- [ ] `spring-web-4.3.6.RELEASE.jar`
- [ ] `spring-websocker-4.3.6.RELEASE.jar`
- [ ] `spring-webmvc-4.3.6.RELEASE-javadoc.jar`
- [ ] `spring-webmvc-portlet-4.3.6.RELEASE.jar`

#### 在使用集合数据绑定时，后台方法中不支持直接使用集合形参进行数据绑定，所以需要使用包装 POJO 作为形参，然后在包装 POJO 中包装一个（）属性？
- [ ] `int`
- [ ] `map`
- [ ] `集合`
- [ ] `String`

#### 下面选项中，哪一个是 Spring 的编码过滤器类？
- [ ] `org.springframework.web.filter.CharacterEncoding`
- [ ] `org.springframework.web.filter.CharacterFilter`
- [ ] `org.springframework.web.filter.CharacterEncodingFilter`
- [ ] `org.springframework.web.filter.EncodingFilter`

#### 下面选项中，不属于整合 SSM 框架所编写的配置文件的是？
- [ ] `db.properties`
- [ ] `applicationContext.xml`
- [ ] `struts.xml`
- [ ] `mybatis-config.xml`

#### 如果拦截器类中的 preHandle() 方法的返回值为（），则程序会继续向下执行处理器中的方法？
- [ ] `TRUE`
- [ ] `return`
- [ ] `全都不对`
- [ ] `FALSE`