Included: data files (lp_adlittle.mat, lp_agg.mat, lp_bandm.mat, lp_blend.mat,
                      lp_brandy.mat, lp_degen2.mat, lp_finnis.mat, lp_recipe.mat,
                      lp_scorpion.mat, lp_stocfor1.mat)
          SKM method files (SKM.m, maxviolatedofsample_constraint.m)
          experiment files (test.m)

To Run: Matlab command ‘test()’ will produce an array containing the table values in 
        “A Sampling Kaczmarz-Motzkin Algorithm for Linear Feasibility”


The data files are linear feasibility problems equivalent to the Netlib LP problems of the 
same name (transformation as given in “A Sampling Kaczmarz-Motzkin Algorithm for Linear 
Feasibility”).  

‘SKM.m’ contains the SKM algorithm as given in “A Sampling Kaczmarz-Motzkin Algorithm for 
Linear Feasibility” and ‘maxviolatedofsample_constraint.m’ is a subroutine which samples
beta of the linear inequalities and selects the most violated constraint.

‘test.m’ runs the experiments described in the table section of “A Sampling Kaczmarz-
Motzkin Algorithm for Linear Feasibility.”  We compare SKM to a Matlab active-set
method and a Matlab interior-point method with the parameters described in ‘test.m’.
