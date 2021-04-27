### Refactoring

code refactoring is the process of restructuring existing computer code—changing the factoring—without changing its external behavior. Refactoring is intended to improve the design, structure, and/or implementation of the software (its non-functional attributes), while preserving its functionality

#### What is the essence of clean code?
When code is clean, you should be able to sit in a comfortable couch, by the fire, with a good drink and dim lights to enjoy the code like you would enjoy your favorite novel.

![img](https://res.cloudinary.com/practicaldev/image/fetch/s--K72xn87h--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://i.imgur.com/oPvcuy2.png)

#### What is functional programming?
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 
- Pure functions
Returns the same result if given the same arguments.
No side effects.
Returns same results with the same given arguments.
- Impure functions.
If it doesn't return the same result it is an impure function.
If it reads external files it is not pure.
Random number generation is also impure.
- Immutability
1) Unchanging over time.
2)Cannot change after it is created.
3)Higher-order functions
4)Takes functions as arguments.
5)Returns function as it's result.
- Filter
Expects a true or false value to determine if the element should or should not be included. If call back is true it will include the element. If false the element will not be included.
