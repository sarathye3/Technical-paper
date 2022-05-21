# MVC (Spring MVC)
## Abstract :
The __MVC__ architecture was developed to make development of web applications in `rapid and parallel` manner. If an MVC model is used to develop any particular web application then it is possible that the application can be developed three times faster than normal development. This is possible because the Model, View and Controller can be developed by three developers parallely at the same time.
___
## Introduction :
 `Model–view–controller` (__MVC__) is a software design pattern commonly used for developing user interfaces that divide the related program logic into three interconnected elements.
 ___

## Model , View , Controller :
### Model : 
A model contains the __data__ of the application. A data can be a single object or a collection of objects.
### View : 
A view represents the provided information in a particular format. Generally, __JSP+JSTL__   is used to create a view page.
### Controller : 
A controller contains the __business logic__  of an application. Here, the  __@Controller__  annotation is used to mark the class as the controller.
![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/MVC-Process.svg/1280px-MVC-Process.svg.png)
___ 

## Spring MVC :
A Spring MVC is a Java framework which is used to build web applications. It also follows the Model-View-Controller design pattern. It implements all the basic features of a core spring framework like Inversion of Control, Dependency Injection. A Spring MVC provides an elegant solution to use MVC in spring framework by the help of __DispatcherServlet__. Here, DispatcherServlet is a class that receives the incoming request and maps it to the right resource such as controllers, models, and views..

In the image given below the __Front Controller__ represents the __Dispatcher Servelet__ and the process happening in the Spring MVC can be understood easily by viewing it 

![Image](https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/images/mvc.png)
## Process behind the scenes :
- After receiving an HTTP request, (__Front Controller__)Dispatcher Servlet consults the Handler Mapping to call the appropriate Controller. 
- The Controller takes the request and calls
the appropriate service methods based on
the used GET or POST method. The
service method will set model data based
on defined business logic and returns view
name to the Dispatcher Servlet. 
- The Dispatcher Servlet will take help
from View Resolver to pickup the defined
view for the request. 
- Once view is finalized, The Dispatcher
Servlet passes the model data to the view
which is finally rendered on the browser.
___
## Advantages of Spring MVC Framework :
- ### Predefined Templates :
    Spring framework provides templates for JDBC,
Hibernate, JPA etc. technologies. So there is no need to write too much code. It hides the basic steps of these technologies. 
- ### Loose Coupling :
    The Spring applications are loosely coupled because of dependency injection.
- ### Easy to test :
    The Dependency Injection makes easier to test the
application. The EJB or Struts application require
server to run the application but Spring framework
doesn't require server. 
- ### Lightweight :
    Spring framework is lightweight because of its
POJO implementation. The Spring Framework
doesn't force the programmer to inherit any class or implement any interface. That is why it is said noninvasive. 
- ### Fast Development :
    The Dependency Injection feature of Spring
Framework and it support to various frameworks
makes the easy development of JavaEE application. 
- ### Powerful abstraction :
    It provides powerful abstraction to JavaEE
specifications such as JMS, JDBC, JPA and JTA. 
- ### Declarative support :
    It provides declarative support for caching,
validation, transactions and formatting.
___
MVC patterns separate the input, processing, and output of an application.
## Conclusion :
 Every framework has its own importance. In the case of Spring MVC it is that rapid and parallel development can be done which saves more time.
## References :
- [Javatpoint](http://www.javatpoint.com/spring-3-mvc-tutorial).
- [spring.io](https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/mvc.html).
