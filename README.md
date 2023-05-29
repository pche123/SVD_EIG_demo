# SVD_EIG_demo
This code shows how to calculate the SVD based on eigenvalue calculations. Mathematically the operation is simple, but a few nuances are left out in the practical implementation (which are typically based on QR decompositions and via householder reflectors, which is much more numerically stable than eigenvalue decompositions). 

However since SVD is normally taught via the eigendecomposition of the covariance matrix, the above numerical method is kept under the hood, and the implementaiton of SVD via eigendecompositions is not addressed (to which point the notion that the eigenvalues of $X^{\intercal}X$ and $XX^{\intercal}$ are not inhenertly linked which means a careful ordering of the eigenvectors etc need to be addressed among minor issues needs to be considered in the computational implementation). 

For this purpose, some sample code is provided here. 
