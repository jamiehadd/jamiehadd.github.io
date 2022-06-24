Included: data files (creditdefault.mat, BreastCancerData.mat)
          SKM method files (SKM.m, maxviolatedofsample_constraint.m)
          experiment files (SKMtest.m, test.m)

To Run: Matlab command ‘test()’ will produce all SVM classification plots given in “A
        Sampling Kaczmarz-Motzkin Algorithm for Linear Feasibility”


The data files are linear feasibility problems which perform the SVM classification of 
the data sets (as described in “A Sampling Kaczmarz-Motzkin Algorithm for Linear 
Feasibility”).  

‘SKM.m’ contains the SKM algorithm as given in “A Sampling Kaczmarz-Motzkin Algorithm for 
Linear Feasibility” and ‘maxviolatedofsample_constraint.m’ is a subroutine which samples
beta of the linear inequalities and selects the most violated constraint.

’SKMtest.m’ tests the method with various input values of lambda and beta while ‘test.m’ 
contains the parameters (lambda, beta, relative residual error bound) which produced the
plots in “A Sampling Kaczmarz-Motzkin Algorithm for Linear Feasibility.”
