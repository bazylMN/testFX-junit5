# TestFX-junit5 template
#### with TestFX, JUnit5 tests for JavaFX application, included as repository code in test project

### Prerequisites
* gradle
* JavaFX application repository code to test

### Initial
* clone repository
* open build.gradle file in IDE (IntelliJ)
* import dependencies with gradle

### Customise TestFX tests
* delete JavaFXSimpleApp package with code
* include your JavaFX application repository code for test
* or include testFX-junit5 template in existing JavaFX application project (without javaFXSimpleApp code)
* import your JavaFX application Main.class in TestFXJUnitAppRunner class (in FxToolkit.setupApplication() method)
* add your test classes with tests cases

### How to run tests:
#### With gradle command:
To run TestFX tests type command:
* 'clean test'

#### With IDE (JUnit):
* run SimpleTestFXJUnitTest / your test class
* or run only method with @Test annotation in SimpleTestFXJUnitTest / your test class

### Reports
Reports are placed in 'build' directory (after running tests with gradle task 'clean test' / 'clean build').
To run report in browser, open 'build\reports\tests\test\index.html' file and choose browser.
