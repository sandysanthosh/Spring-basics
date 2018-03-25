Welcome to the Spring-basics wiki!


https://www.edureka.co/spring-framework

https://docs.spring.io/spring/docs/4.3.12.RELEASE/spring-framework-reference/htmlsingle/



scope

getter setter:

private int id;
private string name;
private Address address;

setter injection:

applicationContext.xml:

<bean id="student" class="com.javatpoint">
<property name="address" value="51,vellore"></property>
<property name="name" value="santhosh"></property>
<property name="id" value="55"></property>
</bean>


main java:

IOC:

ClassPathxmlApplicaitonBean r= new ClassPathxmlApplicaitonBean("applicationConext.xml");
Employee e=(Employee)factory.getBean("student");
e.displayInfo();
