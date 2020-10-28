## MyBatis
-------------------

#### 以下关于 MyBatis 映射文件中 <association> 元素属性的说明错误的是？
- [ ] `fetchType：指定在关联查询时是否启用延迟加载。fetchType 属性有 lazy 和 eager 两个属性值，默认值为 eager`
- [ ] `column：指定表中对应的字段`
- [ ] `property：指定映射到的实体类对象属性，与表字段一一对应`
- [ ] `javaType：指定映射到实体对象属性的类型`

#### 下列关于 MyBatis 的优点的说法错误的是（）？
- [ ] `基于 SQL 语句编程，相当灵活，不会对应用程序或者数据库的现有设计造成任何影响`
- [ ] `很好的与各种数据库兼容`
- [ ] `需要手动开关连接`
- [ ] `与 JDBC 相比，减少了 50% 以上的代码量，消除了 JDBC 大量冗余的代码`

#### 以下有关 MyBatis 映射文件中 <insert> 元素说法正确的是？
- [ ] `useGeneratedKeys（仅对 insert 有用）此属性会使 MyBatis 使用 JDBC 的 getGeneratedKeys() 方法来获取由数据库内部生产的主键`
- [ ] `<insert> 元素用于映射插入语句，在执行完元素中定义的 SQL 语句后，没有返回 结果`
- [ ] `keyColumn 属性用于设置第几列是主键，当主键列不是表中的第一列时需要设置`
- [ ] `<insert> 元素的属性与 <select> 元素的属性相同`

#### MyBatis 的更新操作有关说错误的是？
- [ ] `MyBatis 的更新操作和添加操作时，只需要将 insert() 方法改为 update() 方法即可`
- [ ] `MyBatis 的更新操作执行了 SqlSession 的update() 方法`
- [ ] `MyBatis 的更新操作也需要进行事务提交`
- [ ] `MyBatis 的更新操作在映射文件中是通过配置 <update> 元素来实现的`

#### 对于数据源的配置，MyBatis 框架提供了 UNPOOLED、（）和 JNDI 三种数据源类型？
- [ ] `POOLED`
- [ ] `foreach`
- [ ] `BEFORE`
- [ ] `AFTER`

#### MyBatis 中 <trim> 元素的作用是去除一些特殊的字符串，它的（）属性代表的是语句的前缀，而 prefixOverrides 属性代表的是需要去除的哪些特殊字符串？
- [ ] `value`
- [ ] `foreach`
- [ ] `set`
- [ ] `prefix`

#### （）是当前主流的 Java 持久层框架之一，它与 Hibernate 一样，也是一种 ORM 框架？
- [ ] `spring`
- [ ] `MyBatis`
- [ ] `dubbo`
- [ ] `springmvc`

#### 下面关于 Java 对象之间的关联关系描述正确的是？
- [ ] `一对一的关系就是在本类和对方类中定义同一个类型的对象`
- [ ] `多对多的关系只需要在一方的类中引入另一方类型的集合`
- [ ] `一对多的关系就是一个 A 类类型对应多个 B 类类型的情况`
- [ ] `多对多关联关系需要在本类中引入本类的集合`

#### 以下关于 <select> 元素及其属性说法错误的是？
- [ ] `resultMap 表示外部 resultMap 的命名引用，返回时可以同时使用 resultType 和 resultMap`
- [ ] `<select> 元素用来映射查询语句，它可以帮助我们从数据库中读取出数据，并且装数据给业务开发人员`
- [ ] `parameterType 属性表示传入 SQL 语句的参数类的全限定名或者别名`
- [ ] `在同一个映射文件中可以配置多个 <select> 元素`

#### 在 MyBatis+Spring 的项目中，以下有关事务的相关说法正确的是？
- [ ] `在项目中，数据访问层既是处理业务的地方，又是管理数据库事务的地方`
- [ ] `在 MyBatis+Spring 的项目中，事务是由 MyBatis 来管理的`
- [ ] `进行注解开发时，需要使用 @Transactional 注解来标识表现层中的类`
- [ ] `进行注解开发时，需要在配置文件中配置事务管理器并开始事务注解`

#### ORM 通过描述 Java 对象与数据库表之间的（）关系，自动将 Java 应用程序中的对象持久化到关系型数据库的表中？
- [ ] `全部不对`
- [ ] `映射`
- [ ] `相同`
- [ ] `相似`

#### 当在 MyBatis 文件中使用了 <bind> 元素，在 SQL 语句中可以直接引用元素的（）属性值即可进行动态 SQL 组装？
- [ ] `全部不对`
- [ ] `name`
- [ ] `type`
- [ ] `value`

#### 以下不属于 MapperScannerConfigurer 类，在 Spring 配置文件中使用时需要配置的属性的是？
- [ ] `mapperInterface`
- [ ] `basePackage`
- [ ] `sqlSessionFactoryBeanName`
- [ ] `annotationClass`

#### 下列关于 MyBatis 核心类生命周期说法错误的是（）？
- [ ] `SqlSession 实例时线程不安全的，因此其生命周期应该是请求或方法范围`
- [ ] `SqlSession 实例通常定义为一个类的静态变量`
- [ ] `SqlSessionFactory 实例的生命周期应该在整个应用的执行期间都存在`
- [ ] `SqlSessionFactoryBuilder 实例的最佳作用域是方法范围，也就是定义为本地方法变量即可`

#### MyBatis 的删除操作有关说法错误的是？
- [ ] `MyBatis 的删除操作和添加操作时，也需要封装整个实体类`
- [ ] `MyBatis 的删除操作在映射文件中是通过配置 <delete> 元素来实现的`
- [ ] `MyBatis 的删除操作执行了 SqlSession 的 delete() 方法`
- [ ] `MyBatis 的删除操作也需要进行事务提交`

#### MapperScannerConfigurer 类在 Spring 配置文件中使用时，可以配置的属性及说明错误的是？
- [ ] `sqlSessionTemplateBeanName：指定在 Spring 中定义的 SqlSessionTemplate 的 Bean 名称。如果定义此属性，则 sqlSessionFactoryBeanName 将起作用`
- [ ] `annotationClass：指定了要扫描的注解名称，只有被注解标识的类才会被配置为映射器`
- [ ] `basePackage：指定映射接口文件所在的包路径，当需要扫描多个包时可以使用分号或逗号作为分隔符`
- [ ] `sqlSessionFactoryBeanName：指定在 Spring 中定义的 SqlSessionFactory 的 Bean 名称`

#### MapperFactoryBean 是 MyBatis-Spring 团队提供的用于根据 Mapper 接口生成 Mapper 对象的类，该类在 Spring 配置文件中可以配置的参数不包括？
- [ ] `mapperInterface`
- [ ] `SqlSessionFactory`
- [ ] `SqlSessionTemplate`
- [ ] `basePackage`

#### ORM 就是一种为了解决面向对象与（）中数据类型不匹配的技术？
- [ ] `数据库`
- [ ] `关系型数据库`
- [ ] `全部不对`
- [ ] `非关系型数据库`

#### 有关 MyBatis 配置文件中 <settings> 元素的说法错误的是？
- [ ] `<settings> 元素的配置内容大多数都不需要开发人员去配置它，通常在需要时只配置少数及项即可`
- [ ] `<settings> 元素中延迟加载的全局开关的参数 lazyLoadingEnabled 默认开启`
- [ ] `虽然不配置 <settings> 元素，也可以正常运行 MyBatis，但是熟悉 <settings> 的配置内容以及它们的作用还是十分必要的`
- [ ] `<settings> 元素主要用于改变 MyBatis 运行时的行为，例如开启二级缓存、开启延迟加载等`

#### Spring 与 MyBatis 框架的整合时，可以通过 Spring 实例化？
- [ ] `配置文件`
- [ ] `全部不对`
- [ ] `MyBatis`
- [ ] `Bean`