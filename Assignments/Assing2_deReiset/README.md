# CPSC521_Assign2

In order to test lambda lift there are three test filesfound in the same folder: test1, test2, test3.

*test3 is similar to the case found in the assignment description.

** used modified AST for easier handling of expressions. (examples of these found in the test files)
For any function "f" such that:

f x y z n = ...

replace with 

f (x,y,z,n) = ...

In the test file being used!



To compile and run the main file (linux machine):
from cmd line type:
  1.  ghc main.hs
  2. ./main inputTestFile
  

** TestFile.hs contains all pertinent files for component testing
