# GS lecture 2
* Methods to solve system of equations without determinants:
  1) Elimination:
    * most of the softwares use the same method for solving the equations
    * Step 1 is to multiply the first equation and then subtract it with second so as to eliminate x
    ![i1](assets/Screenshot%20from%202022-11-13%2001-24-06.png)
    * repeat it for y and z such that you get only a particular value of x y and x in their respective columns other are zero
    * the diagonal elements are known as pivots
    * ![i2](assets/Screenshot%20from%202022-11-13%2001-28-57.png)
    * this method fails then if pivot position has zero,and even after exchanging the rows we get zero
    * we have temporary failure where we can exchange rows to remove zero from pivot and complete failure when zero cant be removed from pivot
    * follow the same transformations for b as well
  2) Back substitution:
      *    ![i3](assets/Screenshot%20from%202022-11-13%2001-34-41.png)

* matrix:
  * ![i4](assets/Screenshot%20from%202022-11-13%2001-39-18.png)
  * matrix multiplication can also be viewed in the form of multiplication of rows as shown in the above picture
  * Now for our question if we want to use matrices to solve the equation the first step would be,
  * ![i5](/assets/Screenshot%20from%202022-11-13%2001-44-24.png)
  * the first matrix is known as E21 because it was used to fix the position of the 2nd row 1st column of A
  * the second step is
  * ![i6](assets/Screenshot%20from%202022-11-13%2001-46-26.png)
  * To get from A to U in a single step we multiply E32 and E21 to get a single transformation
  * ![i9](assets/Screenshot%20from%202022-11-13%2001-56-04.png)
  * <b>Remember that AxB is not same as BxA</b>
  * To have row transformations you premultiply the transformation matrix to matrix A, below the matrix P is used to exchange rows
  * ![i7](assets/Screenshot%20from%202022-11-13%2001-50-41.png)
  * To have column transformations you postmultiply the transformation matrix to matrix A,below the matrix P is used to exchange column
  * ![i8](assets/Screenshot%20from%202022-11-13%2001-51-59.png)
  