## Spring
-------------------

#### Spring 包装 Hibernate 之后，关于 findByExample 方法说法正确的是？
- [ ] `是根据对象来找，对象中有的属性都作为条件，包括主键，根据对象来动态的查询`
- [ ] `是根据 SQL 语句来找`
- [ ] `是根据 HQL 来找`
- [ ] `是根据对象来找，对象中有的属性都作为条件，不包括主键，根据对象来动态的查询`

#### 关于 setter 注入和构造注入说法正确的是？
- [ ] `执行效果完全相同`
- [ ] `注入依赖关系注入时机不同`
- [ ] `setter 注入方式依赖对象先注入`
- [ ] `全部不对`

#### Spring 的通知类型不包含？
- [ ] `After return 通知`
- [ ] `Throws 通知`
- [ ] `Return 通知`
- [ ] `Before 通知`

#### 对 Hibernate 的支持主要用到 Spring 的哪个模块？
- [ ] `Spring 核心模块`
- [ ] `Spring ORM 模块`
- [ ] `Spring MVC 模块`
- [ ] `Spring Web 模块`

#### 下面关于 Spring 的说法正确的是？
- [ ] `Spring 是一个 IOC 容器`
- [ ] `Spring 是一个重要级的框架`
- [ ] `Spring 是一个入侵式的框架`
- [ ] `Spring 是一个轻量级的框架`

#### Spring 中，单例意味着每（）只是一个实例？
- [ ] `JVM`
- [ ] `Context`
- [ ] `Thread`
- [ ] `全部都不对`

#### 下面关于 Spring 管理 Bean 的说法正确的是？
- [ ] `Spring 默认利用原型模式管理 Bean`
- [ ] `Bean 在 Spring 容器中有两种管理方式，原型模式和单例模式`
- [ ] `Bean 在 Spring 容器中有两种管理方式，工厂模式和单例模式`
- [ ] `Spring 默认的利用工厂模式管理 Bean`

#### 如何在 Spring 应用中使用 SLF4J？
- [ ] `作为一个 bean`
- [ ] `全不正确`
- [ ] `作为 JDBC 框架`
- [ ] `作为日志框架`

#### 下面是 Spring 依赖注入方式的是？
- [ ] `get 方式的注入`
- [ ] `接口的注入`
- [ ] `set 方式的注入`
- [ ] `配置文件`

#### 看下面的代码，说法正确的是（）？
```
<bean id="before" class="org.springframework.aop.framework.ProxyFactoryBean">
    <property name="proxyInterfaces"></property>
    <value>com.xfaccp.before.BeforeInterface</value>
    <property name="target">
        <ref bean="testBefore" />
    </property>
    <property name="interceptorNames">
        <list>
            <value>beforeAdvisor</value>
        </list>
    </property>
</bean>
```
- [ ] `这段代码是做 AOP`
- [ ] `全部都是`
- [ ] `这段代码是在做代理`
- [ ] `这段代码是做 IOC`

#### 关于 Spring 与 Hibernate 集成，下面说法错误的是？
- [ ] `在 Spring 配置文件中可以通过 Spring 提供的 LocalSessionFactoryBean，来获得 SessionFactory 的实例`
- [ ] `Spring 提供了 HibarnateDaoSupport 类来简化 Hibernate 的使用`
- [ ] `通过 Spring 可以在 Biz 层代码中无需直接实例化 DAO 类，而是通过注入得到`
- [ ] `通过集成 Spring 和 Hibernate，用 Spring 管理程序的依赖关系，将 SessionFactory 注入到 DataSource 中`

#### Spring 包装 Hibernate 之后，关于 merge 方法说话正确的是？
- [ ] `用来修改记录`
- [ ] `先查询记录，后修改`
- [ ] `用来增加记录`
- [ ] `根据主键来判断，如果有主键就修改，没有主键就增加记录`

#### 下面关于 ApplicationContext 的说法正确的是？
- [ ] `提供一些 BeanFactory 的扩展功能`
- [ ] `是 BeanFactory 的实现类`
- [ ] `全部都不对`
- [ ] `功能同 BeanFactory 一样`

#### 下面关于在 Spring 中配置 Bean 的 init-method 的说法正确的是？
- [ ] `init-method 是在最前面执行的`
- [ ] `init-method 在构造方法后，依赖注入前执行`
- [ ] `init-method 在依赖注入之后执行`
- [ ] `init-method 在依赖注入之后，构造函数之前执行`

#### 下面关于 Spring 配置文件说法正确的是？
- [ ] `Spring 配置文件必须叫 applicationContext.xml`
- [ ] `全部都是`
- [ ] `Spring 配置文件可以不叫 applicationContext.xml`
- [ ] `Spring 配置文件只能有一个`

#### Spring 各模块之间关系是？
- [ ] `全部都是`
- [ ] `Spring 的核心模块不是必须的，可以不要`
- [ ] `Spring 各模块之间可以单独存在`
- [ ] `Spring 各模块之间是紧密关系的，相互依赖的`

#### 看下面的代码，说法正确的是（）？
```
<bean id="beforeAdvisor" class="org.Springframework.aop.support.RegexpMethodPointcutAdvisor">
    <property name="advice">
        <ref local="beforeImpl" />
    </property>
    <property name="pattern">
        <value>.*</value>
    </property>
</bean>
```
- [ ] `这段代码是在定义织入`
- [ ] `这段代码是在定义目标对象`
- [ ] `这段代码是在定义切入点`
- [ ] `这段代码是在定义代理`

#### Spring 中 around 通知的目标对象要实现的接口中 invoke 中方法的参数是？
- [ ] `方法`
- [ ] `目标对象`
- [ ] `方法执行参数`
- [ ] `Exception`

#### Spring 中 before 通知的目标对象要实现的接口是？
- [ ] `MethodInterceptor`
- [ ] `AfterReturningAdvice`
- [ ] `ThrowsAdvice`
- [ ] `MethodBeforeAdvice`

#### Spring 如何处理 XML 的编入编出（marshal/unmarshal）？
- [ ] `全部都不对`
- [ ] `提供了它自己的快速、简单的 XML marshaller/unmarshaller`
- [ ] `不支持 marshaller/unmarshaller`
- [ ] `包装了很多库，包括 Jackson 和 JAXB`