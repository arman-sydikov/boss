## Java Web 基础
-------------------

#### 只能够传递字符串类型数据的方式是？
- [ ] `session 对象表单`
- [ ] `表单 URL 重写`
- [ ] `都可以`
- [ ] `隐藏域 setParameter 方法`

#### 以下代码能否编译通过，假如能编译通过，运行时得到什么输出结果（）？
```
<% ("count", new Integer(0)); Integer count = ("count"); %> <%=count %>
```
- [ ] `编译不通过`
- [ ] `可以编译通过，但运行无输出`
- [ ] `可以编译运行，输出 0`
- [ ] `编译通过，但运行时抛出 ClassCastException`

#### Http 协议的状态码（）表示文件没有创建？
- [ ] `400`
- [ ] `500`
- [ ] `404`
- [ ] `200`

#### 自定义标签中，使用属性时，需要在（）文件中配置，使用（）标签？
- [ ] `.tld <attribute/>`
- [ ] `.tld <tag/>`
- [ ] `<attribute/>`
- [ ] `<tag/>`

#### 以下哪句代码可以正常导入核心标签库？
- [ ] `<% taglib prefix = "c" import = "/WEB-INF/" %>`
- [ ] `<% page import = "c" %>`
- [ ] `<% page prefix = "c" uri = "/WEB-INF/"%>`
- [ ] `<% taglib prefix = "c" uri = "/WEB-INF/"%>`

#### 自定义标签的配置文件放在？
- [ ] `classes`
- [ ] `lib`
- [ ] `WebRoot`
- [ ] `WEB-INF`

#### 在编写过滤器时，需要完成的方法是？
- [ ] `doFilter()`
- [ ] `doPost()`
- [ ] `doChain()`
- [ ] `doDelete()`

#### 下面对 servlet 中重定向说法描述错误的是？
- [ ] `源组件的响应结果不会发送给客户端`
- [ ] `使用的是 HttpServletRespons 接口的 sendRedirect() 方法`
- [ ] `sendRedirect() 方法后的代码仍会执行`
- [ ] `源组件和目标组件共享 ServletRequest 对象`

#### Http 请求及响应的正文部分可以是任意格式的数据，要保证接收方能看得懂发送方发送的数据，Http 协议采用（）协议来规范正文的数据格式？
- [ ] `MIME`
- [ ] `FTP`
- [ ] `HTTP`
- [ ] `TCP`

#### J2EE 中，HttpServletRequest 类的（）方法用返回与当前请求相关联的会话，如果没有，则返回 null？
- [ ] `getSession(null)`
- [ ] `getSession(false)`
- [ ] `getSession()`
- [ ] `getSession(true)`

#### J2EE 中，（）类型的（）方法用于得到会话？
- [ ] `HttpSession、getSession`
- [ ] `HttpSession、newInstance`
- [ ] `HttpServletRequest、getSession`
- [ ] `HttpServletResponse、newSession`

#### Servlet 接收请求时，会调用？
- [ ] `doGet`
- [ ] `doPost`
- [ ] `init`
- [ ] `service`

#### 在 JSP 中导入自定义标签的方法正确的是？
- [ ] `无需导入，可直接使用`
- [ ] `<JSP:taglib uri="" prefix=""%>`
- [ ] `文件的 <taglib>`
- [ ] `%@ taglib uri="" prefix=""%`

#### JSP 中有如下代码：
```
<%
Cookie c = new Cookie("name", "admin"); c.setMaxAge(10000);
response.addCookie(c);
%>
```
以下哪句代码可以正确显示"admin"?
- [ ] `${name.value}`
- [ ] `${cookie.name.value}`
- [ ] `${name}`
- [ ] `${cookie.name}`

#### 自定义标签中，HelloTag 继承自 TagSupport 类，其中有如下代码：
```
("HELLO");
```
该 out 对象声明方法为？
- [ ] `PrintWriter out = response.getWriter()`
- [ ] `PrintWriter out = response.getOut()`
- [ ] `JSPWriter out = pageContext.getOut()`
- [ ] `JSPWriter out = pageContext.getWriter()`

#### 某 JSP 中有如下代码：
```
<%
pageContext.setAttribute("a", "page");
request.setAttribute("a", "request");
session.setAttribute("a", "session");
application.setAttribute("a", "application");
%>
```
有：${a} 则显示结果为？
- [ ] `application`
- [ ] `session`
- [ ] `request`
- [ ] `page`

#### 自定义标签中，如果要声明标签参数为必须的，则需要进行哪种配置？
- [ ] `<rtexprvalue>false</rtexprvalue>`
- [ ] `<rtexprvalue>true</rtexprvalue>`
- [ ] `<required>false</required>`
- [ ] `<required>true</required>`

#### 可以执行请求转发的操作是？
- [ ] `JSP 中 response 内置对象的 sendRedirect() 方法`
- [ ] `RequestDispatcher 对象的 include() 方法`
- [ ] `RequestDispatcher 对象的 forward() 方法`
- [ ] `标记`

#### 下面哪一个选项不是 Http 响应的一部分？
- [ ] `协议版本后`
- [ ] `状态行`
- [ ] `响应正文`
- [ ] `响应头`

#### 在 Servlet 中，下列语句可以正确获取 PrintWriter 对象的是？
- [ ] `PrintWriter out = response.getPrintWriter()`
- [ ] `PrintWriter out = request.getWriter()`
- [ ] `PrintWriter out = request.getPrintWriter()`
- [ ] `PrintWriter out = response.getWriter()`