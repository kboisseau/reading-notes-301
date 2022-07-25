Functional programming is a programming paradigm which is a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing state and mutable data.

A pure function is one that returns the same result if given the same arguments and it does not cause any observable side effects.

Pure functions benefits

The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

Given a parameter A → expect the function to return value B
Given a parameter C → expect the function to return value D





Immutability is unchanging over time or unable to be changed. When data is immutable its state cannot change after its created. If you want to change an immutable object, you can not. Instead you create a new object with the new value. 

Referential transparency means a function with always have the same output, given the same input.
