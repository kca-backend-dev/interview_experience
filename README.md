# Horizantal Scalling 
 - Increasing the number of instance
 - Load balancer helps to distribute load accross the instance
 - This is more resistence to failure tolerance as we can route the request to different instance
 - There is a posiblity of data inconsistency
 - It's help full to scale to any level as we can increase number of instance 
# Vertical Scalling 
 - Increasing the physical RAM,Changing/Adding different processor or Adding multiple machines
 - It's more prone the failure tolerance as we have only one machine and
 - As there is only one machine there is less possibility of inconsistency
 - Here Scaling is limited as we can increase Hardware/Ram etc to specific limit byond which we can't do any thing.

# Sorting Techniques
 - Bubbule Sort
 - Selection Sort[Minimum value moving to the begining of the Array ]-- Time Complexity- O(n^2)
 - Heap Sort[Steps from 1 to 3]-- Time Complexity- O(nlogn)
1.Convert Array to binary tree using level order(insert level by level)
2.Then convert to Headp data structure by Heapify
3. Remove the max element from the root node and keep it inside the array from the last
   Finally Array will be sorted 


# Java Script fundamentals 
 ## Prototypical Inheritance in Java Script 
 - Protypical inheritance: Inheritance via prototype property in java script compared to class based approach in java
   ex:var a={type:'general'};
      var  b={
         __proto__:a
      };
    b.type--> will print as **general**
      In the above code if we call type property from **b ** object it still get's the value as the property is inherited  
 from object **a**
 But when we tried add b object own property it will not get the value as it has it's own property from object b and it will get from that as below. 
  var  b={
         __proto__:a,
        type:'specific'
      };
    b.type--> will print as **specific**
## Debouncing and throttling in Java Script 

# Points need to learn
 - Hashmap vs CuncurrentHashmap(Fail fast vs fail safe)
 - When to use HashMap vs LinkedHashMap?
 - HashMap vs LinkedHashMap vs TreeMap ?
 - SOLID design principle of Java?
 - Difference between Bean Fatory vs Application Context container?
 - Different Scopes available in Spring?
 - What is debouncing and throttling in  JavaScript 
- creating custom functional interface
- How to call difference service paralalley in Microservice architecture?
- Atmoic interger and valatile
- What are synthetic events(A synthetic event is a cross-browser wrapper around the browser's native event) and Higher order functions and Higher Order components
- What is event looping 
- what is props drilling in React?
- Can i add new Cluster in kafak ?
- How do you identifiy loop in LinkedList
- Whar rehashing in Hashet/Hash Map?
- How many number of Threads can executed in Cuncurrent HashMap/Hashset parally?
- How can you decarease/reduce  network letency?
- How do you design Load Balancer ?
- What is fail fast and faile safe(CopyOnWriteArrayList) in Java collection?
- How do you handle Client side load balancer and server side load balancer?
- How does indexing works in SQL?
- Primitives vs Object memory allocation difference in Java?
- What is difference betweeen MetaSpace vs permgen ?
- Different React hooks(useEffect,useState)

# Ops Fundamental 
----------------------------------
- **Association** [two object relation ship]
-  Assocation can be referred to as **composition** when one object owns the other object (Car owns Engin)
-  Assocation can be referred to as **Aggregation** when one object just used other object (Team has player/School has students)

# Latest Java 11 features
----------------------------
- Running java file in single command
- New Utility methods in String class-isBlank(),isEmpty()
- Local variable syntax for lamda parameters
- HttpClient


# Rest API Questions
------------------
 - What are indempoton methods in Rest API
  - POST - Not indemton methods- Each time creates resource
  - GET,PUT,HEAD,DELETE,OPTONS--Doesn't change state if we call multiple times( Ref- https://restfulapi.net/idempotent-rest-apis/)
  - SOAP vs REST when to use which one ?
   
# Design Questions
 - Tiny URL desgin
 - Chat mgmt system
 - Parking lot system
 - Load Balancer use case
 - Gateways in Architecture 


# Interview Experience

## SQL
- Find the nth Heightest salary 
- Rank vs Desnk rank
- Union vs Union All
- how do you transform rows into columns



## Random Questions
- @RestControllerAdvice
- How to integrate JPA in Spring Boot
- Sleep vs Wait 
- How do you handle exception in spring.


## Core Java
- Why Java has wait and notify methods in Object class
- How do you prevent modifying the values of class via Reflection process.
- Write Single ton class with Thread safe.
-  Runnable vs Callable --IMP
- Name few GC algorithems
- Do you know GC implementation?


## Kafka Questions
- What is main use case of Kafka?
- How to define topic in Kafka?
- Main Terminogies -False Tolarent,Hight Through Put,Replication Fator 


## Front End Questions
- What are different ways of creating component in React/Angular?
- What is closure in Java Script
- What is function/varible hoisting in JavaScript?
- What is diff let vs var?
- Higher order function vs Higher Order components

## Backend Questions
-----------------------
- OOps concepts,Abstraction,Encapsulsation,Inheritence and Polymorphisam ? Explain with an example
- Why Object oriented programming?
- What Interceptor Design Pattern and Filter concept?
- What is Proxy Design pattern and use case?
- How do you sort elements in Java?
- Comparable vs Comparator? When you will use which?
- What is meant by Metaspace in Java 8?
- How will you handle OutOf Memory Exception?
- How you will handle exception in Java?
- What are ACID properties of Database?
- What are the different methods present in Object Class?
- What problem the MVC Design pattern solves?**
- Why String is Immutable class?
- What are Functional interface?
- How does HashMap internal Working/Implementation ?
- Difference between HashMap vs Hashtable? 
- What are Supplier,Consumer,Fuctional and Predicate in Java?
- Access token vs Refresh token in JWT
- Saga Design pattern implementatoin?
- Kafka or RabitMq Messaging services implementation
- What is use of Weak Hashmap and Cuncurrent Hashmap?
- Difference between CountDownLatch vs CyclicBarrier?
  - **CountDownLatch**: Will be used to completed main task after completing other tasks by decrementing latch count
  - **CyclicBarrier**: Will be used to perform some task in different thread after all the threads are completing the execution 
- Difference between CountDownLatch and Seamaphore in Java
- Reverse the LinkedList elements in Java?
- Can you add String builder in Tree Map?

## Design Pattern
- Singleton,Factory and Prototype
- Adapter Design pattern
- Facade design pattern
- Saga Design Pattern


## Spring Framework Questions
- What are life cycle of spring bean?
- @Component vs @Bean
- @RestController vs @Controller
- DI vs IOC(Invesrion of Control)
- What are Join point and point cuts in AOP?
- What is Compile time weaving and Runtime weaveing?
- What @Asynch in Spring
- Can Rest Webservice Supports other Prortocol ?
- How will you manage new features in Restfull service?
- How do you do Exception handling in Spring?
- How to call Call Storedprocedure in Spring using JdbcTemplate and Jdbc?
- How to handle cache in Spring Restfull service ?[Cache concept in Spring]
- RowMapper class in Spring?
- Spay vs Mock in Junit[Testing]
   -Spay creates actual/real object and stubs method but Mock creates fully/complete mocked object
- How you will Test for exception thrown synarios in Junit?
- How to test the one method return value will be fed for Other method input argument and the result need to validate?
- Difference between AssertEequal vs AssertSame?


## Hibernate Questions
- JPA Repository VS CRUDRepository
- Differents states of Objects in JPA
- Difference between get vs load method?
- Different Annotation in Hibernate?

## Microservice Question
- Design Principle of Microservice Architecture?
- How do you handle Transaction in Microservice Architecture?
- Zuul and Hystix of Microservice?
- Different Isolation levela and Propagation levels in Spring

## Data Base Question
- Function vs Stored Procedures
- When to use Cursor and loops in Database?
- When to use index in database?
- Difference between View vs Materialised view ?
- What is Normalisaton and Denormalisation in Database?
- What are Psedo columns in Databse?
- What is execution plan and Cost of operation in database?
- What are Pseudocolumn in Database?
- What is meant by 2nd/3rd Normalisation form?
- How to check the duplicate records in database table?
## Frontend Questions
- Difference between Angular vs React
- Difference between Promise vs Observable in Javascript?
- What is EventLooping in Javascript?
- What is Event bubbling in JavaScript?
- What is Closure in JavaScript?-A closure is the combination of a function and the lexical environment within which that function was declared
- How does Ajax call works?
- What are heigher order functions in Javascript?
- What are ES6 features?
- What is Redux Thunk?
- What problem Redux solves?
- What is Variable Hoisting in JavaScript?
- Difference between fetch vs Axios?
- Difference between slice vs splice method of String? splice-->Modifies original array but splice will not 
- In React Functional Component how to update state values ?
- Difference between == and ===?
- is undefined===null ?
- Pure vs Fuctional Components?
- Life Cycle of Angular and React(Mouting/Updating/Unmounting phase?)?
- What is Rxjs and different operators present in Rxjs?
- What are different React and Angular LifeCycle methods.?
- How does React converts JSX to html?
- How does React Router works?
- What are Higher Order Components in React?
- What are controlled and Controlled components in React?
- What are Sythatic Events in React?
- How can I call block of Code when the list of AJAX call completes?
- Difference between Asych Await vs Promise?
- What is the difference between AOT( compiles your app at build time on the server) and JIT(compiles your app at build time on the server) in Angular?
- What difference between switchMap vs mergeMap vs concatMap?
- What is difference between concatMap vs combineLatest in Observable?
- Explain Protypephical inheritance in JavaScript with example?
- Import vs Default Import in javaScript?
- Web Workers vs Service Workers?
- What are higher order functions in Javascript?(function Which receives function as argument or function as output-This makes Javascript more functional)
- What are Higher oreder function in react js?.
- What are synthetic events in Reactjs ?
- Bind vs Applay in JavaScript?
## Important Docker Commands
--Need to be added here
-- Docker compose.yml vs docker.yml



## RestFull Service
- Difference between Put vs Patch method?
  - Put Requires to send entire payload of Resporce
  - Patch Requires only Required properties of resource[In Terms Netowrk Banwidth/Utilisation PATCH method will use very less bandwidth]
- what are idempotent methods in restfull service?
  - Idempotent methods- GET/PUT/DELETE(Safe operation)
  - Non Idempotent methods - POST (Non Safe operation)

## Questions on Process/Workflows
- Agile vs Water fall model?
- Agile Terminogies-Sprint,Retrospective,Scrup Master,Product Owner,Velocity,Capacity,Grooming,Planning,Release,Deployment,?
- What is Blue Green Deployment?

