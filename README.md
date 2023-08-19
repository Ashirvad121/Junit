# Junit


# JUnit Examples

This repository contains example code snippets demonstrating various concepts related to JUnit and Mockito testing frameworks. Each package within the repository corresponds to a different topic and contains relevant code examples.

## Contents

- [InstanceVariableDemoInTest](#instancevariabledemointest)
- [MathUtilsTest](#mathutilstest)
- [TestLifeCycleExample](#testlifecycleexample)

## InstanceVariableDemoInTest

This package showcases the usage of instance variables and their behavior within JUnit test methods. It explores how instance variables are affected by the test lifecycle and how they differ from class variables. The main class in this package is `InstanceVariableDemoInTest`.

**Usage:**
- Demonstrates the concept of instance variables and their scope within JUnit test methods.
- Highlights the differences between instance variables and class variables.
- Provides insights into how instance variables are managed across different test methods.

## MathUtilsTest

This package demonstrates unit testing using JUnit for the `MathUtils` class, which contains various mathematical utility methods. The test cases cover scenarios related to integer and double division, as well as primality testing using parameterized tests.

**Usage:**
- Illustrates the creation of unit tests for mathematical utility methods using JUnit.
- Includes tests for integer division, double division, and primality testing.
- Utilizes parameterized tests to test multiple inputs in a single test method.

## TestLifeCycleExample

This package showcases the lifecycle of JUnit tests using the `TestLifeCycleExample` class. It covers the different phases of a test's lifecycle, such as `@BeforeAll`, `@BeforeEach`, `@Test`, `@AfterEach`, and `@AfterAll`.

**Usage:**
- Demonstrates the order of execution for various lifecycle methods in JUnit tests.
- Provides insights into how setup and teardown methods are executed before and after test methods.
- Illustrates the use of class-level setup and teardown methods using `@BeforeAll` and `@AfterAll`.

---

