# Download: AlgART Java Libraries

**Short description: **

## Java libraries for processing arrays and matrices, including image
processing.

  
**Thumbshot: **![](http://www.freewarefiles.com/screenshot/algart1_md.jpg)   
  
**Download link:** [Download AlgART Java Libraries](http://freesoftwares.boysofts.com/AlgART-Java-Libraries_program_95471.html)  
  

**Publisher's Description**  
  

Open-source Java libraries, supporting generalized smart arrays and matrices
with elements of any types (1 bit, 8/16/32/64-bit integers, 32/64-bit floating
point values and any other Java types). The libraries contain a wide set of
2D-, 3D- and multidimensional image processing algorithms: linear filtering,
mathematical morphology, rank operations, spectral transformation (FFT), and
other algorithms, working over arrays and matrices.

There is also skeletonization and measuring of binary images. The libraries
use 63-bit addressing of array elements (all indexes and length are
represented by 64-bit long type). So, itA's theoretically possible to create
and process arrays and matrices containing up to 2^63-1 (~10^19) elements of
any primitive or non-primitive types, if OS and hardware can provide necessary
amount of memory or disk space. Memory model concept allows storing AlgART
arrays in different schemes, from simple Java arrays to mapped disk files; all
necessary data transfers are performed automatically while every access to an
element or a block of elements.

Most of algorithms are based on wide usage of lazy evaluations. Typical
operations, like elementwise summing or geometrical matrix transformations,
are implemented via lazy views of the source array or matrix. For example, you
can take a multidimensional matrix, rotate it (or perform any other affine or
projective transform), and then extract a submatrix from the result. All these
operations will be performed virtually (not requiring time), and actual
calculations will be performed only at the moment of accessing elements,
usually while copying the resulting matrix to a newly created one.

Moreover, in many cases the libraries will A'understandA' itself, that the
user wants to perform rotation or another transform, and will split the matrix
into suitable rectangular blocks (fitting in RAM) and choose the best
algorithm for this task at the moment of copying operation.

These libraries require JDK 1.5+

  
  
Screenshot: ![](http://www.freewarefiles.com/screenshot/algart1.jpg)  
**For more freeware softwares visit [Freeware software downloads.](http://freesoftwares.boysofts.com/)**   
**And [Free softwares and php script downloads.](http://www.boysofts.com/)**

