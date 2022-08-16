# Big O Notaton
* Helps remove the necessity of asking about the performance of your machine or the language and focus on what is true across all resources.
* O(n) - n is a variable representing the input. It can be any variable a-z
* Time Complexity - A way of showing how the runtime of a function increases as the size of the input increases
* Linear Time - Runtime scales linear to the size of the input O(n) 
* Constant Time - Runtime remains same regardless of input O(1)
* Quadratic Time - Runtime is quadratic O(n²)
* Coefficient - a numerical or constant quantity placed before and multiplying the variable in an algebraic expression
* Linear function equation(y = f(n) = a + bn) - A graph that has a straight line 
  * a - is the constant term or the y intercept. It is the value of the dependent variable when n = 0.
  * b - is the coefficient of the independent variable. It is also known as the slope and gives the rate of change of the dependent variable.
* Drop Coefficients (T = an + b) Drop "a"
* Quadratic Equation: ax^2 + bx + c = 0
  * a, b and c are known values. a can't be 0.
  * "x" is the variable or unknown (we don't know it yet).

```javascript
  // T = c = 0.115
  // T =  Time
  // c = constant
  // 0.115 * 1 = O(1)
  // Constant time
  (array) => {
    total = 0; // Has no dependency on <array> so it is constant O(1)
    return total; // Has no dependency on <array> so it is constant O(1)
  }
```

