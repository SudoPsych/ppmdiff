# ppmdiff
Image comparison program for the csc411 arith assignment.
This code works for images that have a maximum difference in width or height of one.
Array2 is identical to Proffesor Daniels implementation and is thus compatible with it.

To get this working run the following lines within the ppmdiff directory:

cargo build --release
./target/release/ppmdiff ppm_images/f79.ppm ppm_images/f78.ppm

Your result should be:
0.0620142967525952

Building the executable may take a while, just a heads up.
