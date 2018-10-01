# Finite Difference Methods for 1st and 2nd Derivatives




* Using a FD method for the interior points was as simple as applying the appropriate stencil.
* To find the derivates at the boundary points, I expanded the points and used the method of undetermined coefficients.
* I used the infinity norm to see what order of accuracy the worst point in the approximation had.
* For uniformly increasing points both methods were 2nd order accurate, but for any non-uniform grid the accuracy dropped to constant or worse. 
* The final matrix operations are `diffmat2` and `diff2mat` for the first and second derivatives.