Spring解密 读书笔记		
第一部分 掀起Spring的盖头来		
	第1章 Spring框架的由来 		
第二部分 Spring的IoC容器		
	第2章 IoC的基本概念		
	第3章 IoC Service Provider		
	第4章 Spring的IoC容器之BeanFactory 		
	第5章 Spring IoC容器ApplicationContext 		
	第6章 Spring IoC容器之扩展篇 		
第三部分 Spring AOP框架			
	第7章 一起来看AOP 		
	第8章 Spring AOP概述及其实现机制 		
	第9章 Spring AOP一世 		
	第10章 Spring AOP二世 		
	第11章 AOP应用案例 		
	第12章 Spring AOP之扩展篇 		
第四部分 使用Spring访问数据		
	第13章 统一的数据访问异常层次体系 		
	第14章 JDBC API的最佳实践 		
	第15章 Spring对各种ORM的集成 		
	第16章 Spring数据访问之扩展篇 		
第五部分 事务管理		
	第17章 有关事务的楔子 		
	第18章 群雄逐鹿下的Java事务管理 		
	第19章 Spring事务王国的架构 		
	第20章 使用Spring进行事务管理 			
	第21章 Spring事务管理之扩展篇 		
第六部分 Spring的Web MVC框架		
	第22章 迈向Spring MVC的旅程 		
	第23章 Spring MVC初体验 		
	第24章 近距离接触Spring MVC主要角色 		
	第25章 认识更多Spring MVC家族成员 		
	第26章 Spring MVC中基于注解的Controller 		
	第27章 Spring MVC之扩展篇 		
第七部分 Spring框架对J2EE服务的集成和支持			
	第29章 Spring框架对JMS的集成 		
	第30章 使用Spring发送E-mail 		
	第31章 Spring中的任务调度和线程池支持 		
	第32章 Spring框架对J2EE服务的集成之扩展篇 		
	第33章 Spring远程方案		



第一部分 掀起Spring的盖头来
	第1章 Spring框架的由来 
		略...
第二部分 Spring的IoC容器
	第2章 IoC的基本概念
	第3章 IoC Service Provider
	第4章 Spring的IoC容器BeanFactory 
	第5章 Spring的IoC容器ApplicationContext
	第6章 Spring的IoC容器扩展篇
	
	第2章 IoC的基本概念
    		IOC全称Inversion of Control，中文名，“控制反转”或“依赖注入”。
		
		依赖注入方式：构造方法注入、setter方法注入、接口注入
		使用IOC后，对象具有更好的可测试性、可重用性、可扩展性。IOC可以帮助我们解耦各个业务对象间的依赖关系的对象绑定方式。	
	第3章 IoC Service Provider
		IoC Service Provider是一个抽象出来的概念，它可指代任何将IoC场景中的业务对象绑定到一起的实现方式。它可是一段代码，一组相关的类，甚至是IoC框架。
		IoC Service Provider的职责：业务对象的构建管理、业务对象间的依赖绑定
		业务对象间的依赖关系绑定方式
			直接编码方法
			配置文件方式（普通文本文件、properties文件、 XML文件）
			元数据方式（注解）
	第4章 Spring的IoC容器BeanFactory
		    Spring的IoC容器是一个IoC Service Provider,是一个提供IoC支持的轻量级容器，除了基本的IoC支持，还提供了相应的AOP框架支持、对象生命周期管理、
    线程管理、企业级服务集成等服务。
		Spring提供了两种容器类型: BeanFactory和ApplicationContext。
		    BeanFactory。基础类型IoC容器，提供完整的IoC服务支持。默认采用延迟初始化策略(lazy-load)。
		    ApplicationContext。ApplicationContext在BeanFactory的基础上构建，还提供了其他高级特性，如事件发布、国际化信息支持。
		
		图。。。。。



	
	
	
	第5章 Spring的IoC容器ApplicationContext
	
	第6章 Spring的IoC容器扩展篇
	
