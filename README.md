SOLID Design Principles Notes:

Single Responsibility Principle  -

•	Makes your software easier to implement and prevents unexpected side-effects of future changes.

•	Make sure that each class has only one responsibility.

•	Reduces the number of bugs and improves your development speed.

•	Make sure to not oversimplify your code because later you might have to put a bunch of dependencies which makes the code unreadable and confusing.

•	Ask yourself: What is the responsibility of your class? If your answer includes the word “and”, you’re most likely breaking the single responsibility principle.

Open/Closed Principle -

•	Promotes the use of interfaces to enable you to adapt the functionality of your application without changing the existing code.

•	Uses interfaces instead of superclasses to allow different implementations.

•	Benefit of this approach is that an interface introduces an additional level of abstraction which enables loose coupling.

Liskov Substitution Principle –

•	Enables you to replace objects of a parent class with objects of a subclass without breaking the application.

•	Requires all subclasses to behave in the same way as the parent class.

•	Subclasses need to follow these rules:

    o	Don’t implement any stricter validation rules on input parameters than implemented by the parent class.

    o	Apply at the least the same rules to all output parameters as applied by the parent class.

Interface Segregation Principle –

•	Prevent bloated interfaces that define methods for multiple responsibilities.

•	Avoid classes and interfaces with multiple responsibilities because they change often and make your software hard to maintain.

•	“Clients should not be forced to depend upon interfaces that they do not use.” – Robert C .Martin

•	Reduces the side effects and frequency of required changes by splitting the software into multiple, independent parts.

Dependency Inversion –

•	Introduces an interface abstraction between higher-level and lower-level software components to remove the dependencies between them as long as you don’t change any interface abstractions.

•	Needs to consequently apply the Open/Closed and the Liskov Substitution principles to your code.  

