1. What is "N + 1" problem in REST APIs and how would you solve it?
-> N+1 is a situation where our application called ther server N+1 time to fetching the one resource.
To solve this issue we need to add required information into parent resource so we don't want to call child resource and
this way we can less the server call.

2. When do you stop writing unit tests?
-> If we are use Test Driven Development(TDD) then we can stop writing unit tests. Basically,
Test Driven Development (TDD) is software development approach in which test cases are developed to specify and validate what the code will do.
So this will avoid the code duplication.

3. Why would one use monorepos?
-> We are use monorepos because we have to manage single resource for a team, easy to share, easily reuse code,
one operation make a change to multiple projects.

4. What is Liskov substitution principle?
-> It defines that objects of a superclass shall be replaceable with objects of its subclasses without breaking the application.
Which requires the objects of your subclasses to behave in the same way as the objects of your superclass.

5. How do you avoid race conditions?
-> For avoiding race conditions we need to make sure that critical section is executed as an atomic instruction.
this means that once a single thread is executed then another thread will execute.

6. What is the first thing you do when you encounter a bug?
-> I just flow below steps:
1) Trying to understand the bug
2) Find the reason of bug
3) Debug the code
4) Try & error appropriate code for resolve the bug.
5) Test whole scenario with different ways which are the possibility of encounter an error.
