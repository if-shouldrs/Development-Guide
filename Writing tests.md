This file will be edited as I gain more experience with all kinds of tests.

# Unit Testing
When writing code using TDD, you always start with the tests. I'll go over the most important pointers about unit testing.

## Only Test Business Logic
The tests themselves should be self contained and not access anything unless it's through the business logic that is being tested. That means, no accessing DBs, web resources, different modules.

## No Dependance on Implementation Details
The test code defines the behaviour your actual code is supposed to have, and should work regardless of what data structure or method calls you're using inside the methods you're calling. You may be tempted to adjust your test case to make your code pass the test, and this rule of thumb is here to make you stop and think of which box your change lands on. Ideally you don't change your test once you start writting the code to be tested.

# Integration Testing
If you develop with [SOLID](SOLID.md) principles in mind you'll end up with classes/modules dedicated to interfacing with external libraries and APIs in order to make your code be easier to update & maintain. The tests written for these modules are called Integration Tests and they confirm that our integrations are producing the expected result, both because we wrote them correctly and because those external dependencies are still behaving as we expect them to.

# Assurances
The idea behind testing is to provide assurances. Integration tests assure us we can rely on our dependencies, business logic unit tests assure us our business logic is sound, etc.
