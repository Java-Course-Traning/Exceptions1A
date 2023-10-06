# Exercise 1 - Basics and Exception Testing

## Tasks
### Exercise 1A:
Create a java application with a main class named `"App"` and a `main` method declared in it.

Write a method named `"lookupCity"` in class App which takes an integer as an input and outputs the nth element of an array of strings.

The String array is defined as:

`String[] CITIES= {"Cairo", "Damascus", "London", "Paris", "Rome", "Teheran"};`

The method should throw a ArrayIndexOutOfBoundsException if n is bigger than 5.

Call it from `main` with n = 6 and verify that the stacktrace features the complete stack of calls from `main` down to `lookupCity`.

The solution should contain a test class `"AppTest"` with the following tests:

**T1:** a test to check that no exception is thrown with n = 0, using JUnit5 assertions.

**T2:** a test to check that an ArrayIndexOutOfBoundsException is thrown with n = 6, using JUnit assertions.

**T3:** a test to check that an ArrayIndexOutOfBoundsException is thrown with n = 6, using AssertJ assertions.