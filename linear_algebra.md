## Linear Algebra
---
####Linear Dependence: 
* A family of vectors is a **linearly independent** family if none of them can be written as a **linear combination** of finitely many other vectors in the family
* We know two vectors specify a plane. If a third vector exists there, and it can be described as a linear combination of the previous two, then its linearly dependent.
* If one of the vectors in the set can be described as a linear combination of any others, removing it does not affect the span of the set!


####**Span:** 

* Span, or the reach of a set of vectors, is the space that can be represented by scaling up and down all the vector columns available to us in a matrix
* Given a set of vectors, what other vectors can you create by adding and/or subtracting scalar multiples of those vectors. The set of vectors that you can create through these linear combinations of the original set is called the "span" of the set.
* For example, the span of the set of two 3-d vectors is a plane
Example: The span of the set   

$$  $$ 

* is all the linear combinations possible through combining both vectors, thus defining a plane in R^3 whos equation is  2x + y -3z = d
 
####$$ A\hat{x} = \hat{b}$$:
* Given a matrix A, can we solve: for every possible vector b? In other words, do the linear combinations of the column vectors fill the xy-plane (or space, in the three dimensional case)? 
* If the answer is “no”, we say that A is a singular matrix. In this singular 
case its column vectors are linearly dependent; all linear combinations of those 
vectors lie on a point or line (in two dimensions) or on a point, line or plane (in 
three dimensions). The combinations don’t fill the whole space. 
####Cartesian Product $$ a X b$$:
*  If A is a set {a,b} and B is another set {1,2,3}, the Cartesian product of the two, denoted by A x B equals {(a,1),(a,2),(a,3),(b,1),(b,2),(b,3)}
It basically forms a grid, or a volume or a 4d abstract dimensional space
*  ℝ, is the set of all real numbers.  $$R^2$$ forms the infinite amount of coordinate pairs into a grid, $$R^3$$ forms an infinite amount of coodinate triplets, into a volume basically.
*  $$ R^n $$ is the cartesian product of n sets of R. This is the set of n-tuples. In linear algebra it's the set of all vectors in n-dimensional space. 
Rn = Infinitely large set of vectors each with N components each

#### Vector Space
* All the space that can be reached through scalar multiplication and vector addition of a given set of vectors
* A vector space need not be two directions, but in fact can consist of an abstract infinite dimesion space
* When we say the vectors can be scaled in any way, they can also be scaled by complex numbers
* In a vector space it is paramount that no matter how many, or which kind of scalings, you do with the individual vectors and no matter how you add them, **you will always remain in the vector space**
* vector spaces are characterized by their **dimension**, which specifies the number of independent directions in the space
 
#### Subspace
* A subspace of a vector space is just a subset of the elements(vectors) that in and of themselves form a vector space.
* If a subset has the following 3 properties than it is a subspace:
1) the zero vector is in the subset so 
$$ \{0,0,0,0...0_n \} $$







