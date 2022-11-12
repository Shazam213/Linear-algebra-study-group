# GS lecture 3
### Matrix multiplication
* Matrix multplication can be viewed in a different sence as in for C=AxB we can assume that each column of B is being multiplied by matrix A to give the corresponding columns of C
* Also we can assume that each row of A i being multiplied by the matrix B to give corresponding rows of C
* ![i1](assets/Screenshot%20from%202022-11-13%2002-32-15.png)
* A special case arrises when we multiply columns of A and rows of B then we get a full sized matrix C in which each column is a multiple of columns of A and each row is a multiple of rows of B
* ![i2](assets/Screenshot%20from%202022-11-13%2002-37-23.png)
* ![i3](assets/Screenshot%20from%202022-11-13%2002-37-53.png)
  the row space and column space for such a matrix is just a line that is all the rows and all the columns of matrix C lie in the same lines respectively
* You can also divide the A and B in blocks and then multiply the blocks as normal matrix multiplication and still get the same result
* ![i4](assets/Screenshot%20from%202022-11-13%2002-43-53.png)

### Inverse of matrices
* The matrices whose inverse exists are known as invertible or non-singular matrices
* A matrix is said to be singular or non-invertible if you can find a vector X such that AX=0 where X is not 0
* ![i5](assets/Screenshot%20from%202022-11-13%2002-49-36.png) 
* Suppose inverse does exist then we can consider it as:
* ![i6](assets/Screenshot%20from%202022-11-13%2002-52-55.png)
* ![i7](assets/Screenshot%20from%202022-11-13%2002-55-53.png)
* 