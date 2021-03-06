1104-feel-string-length-function-test
--------------------

### Description ###

DMN Model [1104-feel-string-length-function-test.dmn](./1104-feel-string-length-function-test.dmn) tests DMN specification conformance of `FEEL built-in function 'string length(string)'`.

#### Specification Reference(s): ####
 * DMN 1.1 - 10.3.4.3 Table 60

### Test Cases ###

|Decision Name| Literal Expression (FEEL) | Expected Result|
|-------------|-------------------------- |----------------|
|feel-string-length-function-test_1|string length("")|0 (number)|
|feel-string-length-function-test_2|string length("a")|1 (number)|
|feel-string-length-function-test_3|string length("abc")|3 (number)|
|feel-string-length-function-test_4|string length(string:"xyz123")|6 (number)|
|feel-string-length-function-test_5|string length(string:"aaaaa dddd")|10 (number)|
|feel-string-length-function-test_6|string length(string:"aaaaa dddd ")|11 (number)|

         

### Disclaimer ###
This page is a simple view for the underlying DMN model file [1104-feel-string-length-function-test.dmn](./1104-feel-string-length-function-test.dmn).
The purpose of the model is to test and validate FEEL expressions. Therefore the underlying DMN model is simplistic:
Each decision node contains one literal expression under test. The table above shows the decision, the underlying FEEL expression and the expected result.

Site generated by [ACTICO GmbH](https://actico.com) for [Technology Compatibility Kit (TCK)](https://dmn-tck.github.io/tck/) for the Decision Model and Notation (DMN) standard.

[DMN 1.1. Specification Document](http://www.omg.org/spec/DMN/1.1/) 
  