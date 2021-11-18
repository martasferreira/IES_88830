# IES_88830
##lab3



### Review Questions

### a)

A @Controller corresponds to the typical MVC Controller.
The @RestController is a combination of both the @Controller and @ResponseBody annotation.
@Controller creates a Map of Model Object and finds a view while @RestController simply returns object and object data directly written into http response as JSON orXML.  

### b)


### c)

The annotations @Table, @Column, @Id found in the Entity are JPA annotations that serve to specify a Table of the Entity, map the the entity attribute to the database column and specify the Entity identifier.

### d)

Autowiring feature of spring framework enables you to inject the object dependency implicitly. It internally uses setter or constructor injection.

Autowiring can't be used to inject primitive and string values. It works with reference only.
