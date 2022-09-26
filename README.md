# Design_Patterns_Cheat_Sheet
C++ Design Patterns examples <br>

Resources: <br>

* Ilustrated guide: https://refactoring.guru/design-patterns <br>
* Bible of Design Patterns: https://github.com/kamranahmedse/design-patterns-for-humans#types-of-design-patterns <br>
* Factory with cpp: https://youtu.be/XyNWEWUSa5E <br>
* Clean architecture folders distribution: https://youtu.be/bdnpXzgj1oY?t=347 <br>
* LARGE TUTORIAL with ASP.NET 6 REST API with CLEAN ARCHITECTURE & DDD: https://youtu.be/fhM0V2N1GpY <br>
* BEST --> Repository-Service Pattern: https://exceptionnotfound.net/the-repository-service-pattern-with-dependency-injection-and-asp-net-core/ <br>
* JWT implementation on .Net: https://jasonwatmore.com/post/2021/12/14/net-6-jwt-authentication-tutorial-with-example-api <br>
* Another JWT implementation: https://sandrino.dev/blog/aspnet-core-5-jwt-authorization <br>
* Builder Pattern example: https://youtu.be/1bL7jX7iK0o <br>


<br>
Repository-Service + Clean Example: <br>
Student<br>
	-> Application (Use cases, API calls for that controller)<br>
		&ensp;--> StudentController<br>
    &ensp;--> StudentService (here you manipulate the answer from Infrastructure)<br>
    &ensp;--> IStudentService (Interface to stablis service methods)<br>
	-> Domain (Model and Repository)<br>
		&ensp;--> StudentModel<br>
		&ensp;--> IStudentRepository (Interface to be used on Infraestructure)<br>
	-> Infraestructure (Bases de datos, Mysql, SQL... )<br>
		&ensp;--> MsyqlStudentRepository<br>
		&ensp;--> SQLStudentRepository<br>
		&ensp;--> RedisStudentRepository<br>
Product<br>
.<br>
.<br>
.<br>
