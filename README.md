# Pros and Cons of Test Driven Development

### Pros
The main benefit of test driven development is that it forces developers to think about the system and how it will work before they begin implementing it with code. In writing tests first, this forces the developer to really think about what the functionality of each part of the system should be instead of just having a vague goal and writing code until you get there. This will lead to a much higher percentage (almost if not all) of the code base being covered by tests. Also, these tests can work as a sort of documentation for other developers to help them understand what the inputs and outputs of each function should be. TDD also helps with writing better quality code as it can catch errors as the programmer is writing the code and can help the programmer to not write extra unnecessary code as they are specifically writing to make the tests pass.

### Cons
A disadvantage of test driven development is that it can add a significant amount of work and time to start developing the system. The developer needs to write all the tests before they can actually start writing the implementation of the system. This can be difficult if the developer doesn't have a solid grasp of how the entire system should work. Also, if all of the team members are not coordinated and don't fully test their components of the system then the test coverage won't be very high. If a bug is introduced in the test then a developer can implement something incorrectly and introduce more bugs into the system. Also, if the requirements of the system change then it requires the extra work of changing all the tests along with the implementation code.



### Test Case
https://github.com/ECE444-2023Fall/project-1-web-application-design-group15-crispycritters/blob/test-user-endpoint/backend/tests/test_server.py#L4-L33