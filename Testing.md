JUnit4 testing for the game and all the game objects.


* Testing types

In this project, we used different ways to test the functionality of the game, so that various situation users might encounter can be all considered. 

For methods that directly return a certain value, we set up test cases of different values to test whether the methods would return the right result. For example, this test below:

![image](uploads/61c5ee5b3264b332081b1d6dc32817dc/image.png)

For methods that require user input, we use InputStream to setup possible inputs that the user might enter. Then, based on different inputs, we generate different test cases to handle different results. For example, in this test below:

![image](uploads/d4d742411620c3046a67bd1a0866b029/image.png)

The following command tests are to test by passing commands

![image](uploads/3a05befff95bd0bcfdc6f8ef01d8d3dc/image.png)

![image](uploads/3e53f75d57a54fed0146735acfc161f6/image.png)

