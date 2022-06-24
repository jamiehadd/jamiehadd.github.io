Included: data files (lp_adlittle.mat, lp_agg.mat, lp_bandm.mat, lp_blend.mat,
                      lp_brandy.mat, lp_degen2.mat, lp_finnis.mat, lp_recipe.mat,
                      lp_scorpion.mat, lp_stocfor1.mat)
          SKM method files (SKM.m, maxviolatedofsample_constraint.m)
          experiment files (SKMtest.m, test.m)

To Run: Matlab command ‘test()’ will produce all Netlib plots given in “A Sampling
        Kaczmarz-Motzkin Algorithm for Linear Feasibility”


The data files are linear feasibility problems equivalent to the Netlib LP problems of the 
same name (transformation as given in “A Sampling Kaczmarz-Motzkin Algorithm for Linear 
Feasibility”).  

‘SKM.m’ contains the SKM algorithm as given in “A Sampling Kaczmarz-Motzkin Algorithm for 
Linear Feasibility” and ‘maxviolatedofsample_constraint.m’ is a subroutine which samples
beta of the linear inequalities and selects the most violated constraint.

’SKMtest.m’ tests the method with various input values of lambda and beta while ‘test.m’ 
contains the parameters (lambda, beta, relative residual error bound) which produced the
plots in “A Sampling Kaczmarz-Motzkin Algorithm for Linear Feasibility.”
