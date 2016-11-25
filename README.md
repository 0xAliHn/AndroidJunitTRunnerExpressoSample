# AndroidJUnitRunner and Expresso sample

The new android test runner brings Junit4 support to android testing. This samples gives a quick
overview of some of the new features like test annotations, parameterized tests and test suite
creation.

1. CalculatorTest.java contains JUnit4 style unit tests for the calculator logic.
1. CalculatorAddParameterizedTest.java contains JUnit4 style tests and uses the @Parameters annotation
   to parameterize a single test with different values.
1. CalculatorInstrumentationTest.java uses JUnit4 style tests to test the Ui of the CalculatorActivity
1. OperationHintInstrumentationTest.java uses JUnit3 style tests to test the Ui of the CalculatorActivity


#Test steps
   Create the test configuration with a custom runner: `android.support.test.runner.AndroidJUnitRunner`
   
    * Open *Run* menu | *Edit Configurations*
    * Add a new *Android Tests* configuration
    * Choose a module
    * Choose which tests to run. Click on Test: class and select one of the TestSuites
    (AndroidTestSuite, UnitTestSuite, InstrumentationTestSuite)
    * Add a *Specific instrumentation runner*: `android.support.test.runner.AndroidJUnitRunner`

