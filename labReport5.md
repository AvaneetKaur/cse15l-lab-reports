# Lab Report 5
## Part 1: Debugging

1. Edstem Post1 ![Image](post1.png) ![Image](post2.png)
2. TA's response: When you are changing the values of `arr` in the `reverseInPlace` method you are not keeping track of what the original values are. You need to create another variable which stores the original value of `arr` at specific index before geting changed. 
3. Edstem Post1 ![Image](post3.png) ![Image](post_4.png) ![Image](post_5.png) ![Image](post6.png)
4. TA's response: You are changing values of two variables in the same iteration, so should the for loop still run for `arr.length` many times? Also one of your JUnit tests does not have of correct expected value.
5. 
6. 
