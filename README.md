### -----------------------------------   Unittest_Pytest   ----------------------------------------- :
**Requirements** : VsCode <br>


**UnitTest and PyTest** are Python unit testing frameworks. Often referred to as "**PyUnit**," **UnitTest** is the Python version of **JUnit**, which is a Java-based testing framework.<br>
Both **UnitTest and PyTest** support test automation, sharing of setup and teardown code for tests, aggregation of tests into collections, and independence from the reporting framework.<br>

I want to test a simple method found in the file inc-dec.py, which contains methods for incrementing and decrementing. We will use both UnitTest and PyTest to test this method.<br>
##### ----------------------------------  How to Test Using UnitTest  -------------------------------------------:<br>
Testing with UnitTest is straightforward. Here are the steps:<br>
> Import the UnitTest framework : **import unittest**<br>
> Create a test class. You can refer to the file test_unittest.py in my repository for an example.<br>

##### ---------------------------------   How to Test Using PyTest   ----------------------------------------------:<br>
Testing with PyTest is also simple. Follow these steps:<br>
> Set up PyTest: pip install -U pytest<br>
> Add PyTest to the system environment variable.<br>
> Check the version of PyTest : **pytest --version**<br>
> Create a method to test the code. Refer to the file test_pytest.py in my repository for an example.<br>

------------------------------------------------------------------------------------------------------------------------------------
