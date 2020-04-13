# Spring Framework

Spring Framework 框架的 [API](https://spring.io/projects/spring-framework#learn) 和 [DOC](https://spring.io/projects/spring-framework#learn)

Spring Framework 框架 [源码Github地址](https://github.com/spring-projects/spring-framework)

Spring IOC

        简介、注入方式、依赖关系、依赖绑定方式、XML、注解

Spring AOP

        简介、AOP的关键词、AOP示例
        
简介

Spring AOP 采用**动态代理**和**字节码生成技术**实现。动态代理机制和字节码生成技术都是在**运行**期间为目标对象生成一个**代理对象**，而将横切逻辑织入到这个代理对象中，系统最终使用的是织入横切逻辑的代理对象，而不是真正的目标对象。

```javaScript
/**
*   代理模式简介
*       代理模式中的4个角色
*       1、被访问者的抽象接口
*       2、被访问者的抽象接口的实现类
*       3、代理类  实现了抽象接口，并持有抽象接口实现类的引用
*       4、访问者类
*
*   执行流程：访问者类访问代理类，代理类调用接口实现类。代理类可在调用前后执行相关逻辑。
*/
```

动态代理

使用动态代理，可以为指定的接口在系统运行期间动态地生成代理对象。

动态代理主要由一个类和一个接口组成。java.lang.reflect.Proxy和java.lang.reflect.InvocationHandler接口

缺点：使用动态代理，必须实现相应接口

字节码生成技术

原理：对目标对象进行继承扩展，为其生成相应的子类，而子类可以通过覆写来扩展父类的行为。让系统使用扩展后的目标子类，就可以达到与动态代理相同的效果。使用CGLIB结束可在运行期间动态创建目标子类。

```javaScript
/**
*   AOP 中的关键字
*/

```


Spring 扩展
