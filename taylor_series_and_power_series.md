# Taylor Series

###$$\sum_{n=0} ^ {\infty} \frac {f^{(n)}(a)}{n!} \, (x-a)^{n}$$


##### Many functions can be written as a Power Series about some point of their domain about the origin. The approximation of a function as an infinite sum of polynomials of all degrees, calculated from the function's derivative at a certain point is called the function's Taylor Series.


$$f(a)+\frac {f'(a)}{1!} (x-a)+ \frac{f''(a)}{2!}(x-a)^2+\frac{f'''(a)}{3!}(x-a)^3+ \cdots.$$




![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Exp_series.gif/220px-Exp_series.gif)


###Radius of Convergence $$ \vert x\vert \>R $$:

* The interval of X values for which a given function converges/tends to zero is called the Radius of Convergence. In the complex plane, it truly is a circle of values, while in the real line it is only an interval 
* e.g: The geometric series only converges for |x| < 1

 
$$1 + a + a^2 + \dots = \frac{1}{1-a}\quad \text{for}\  \vert a \vert \< 1 $$ 

* Where R equals 1, the radius of convergence.

### Taylor's Formula for finding the coefficients of the power series

$$ f(x) = a_0 + a_1x + a_2x^2 + \cdots$$

differentiate:

$$ f'(x)= a_1 + 2a_2x + 3a_3x^2 + \cdots $$

Plug in 0 for x and all other terms go to zero except a_0. For the double integral, the same thing happens except for a_1. Ultimately the equation for the coefficient boils down to: 

$$ f(x) = a_n = \frac{1}{n!}f^{n}(0)$$

## Example 1.


![](http://s5.postimg.org/j5s06kog7/taylor_series_prob.jpg)

# Taylor Theorem for Errors

Taylor's theorem describes the asymptotic behavior of the remainder term

$$ R_n(x) = f(x) - P_n(x) $$

![](http://s5.postimg.org/99qx6xio7/residual.jpg)

### Example:

![](http://s5.postimg.org/n4p7ped3b/residue2.png)
