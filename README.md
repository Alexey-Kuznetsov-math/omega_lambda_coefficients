# omega_lambda_coefficients
Supplementary materials to the paper "Simple and accurate approximations to the Riemann zeta function" by A. Kuznetsov, Journal of Computational and Applied Mathematics, Vol. 488, 2026, 117791. https://doi.org/10.1016/j.cam.2026.117791.

The coefficients omega_{p,j} and lambda_{p,j} are given in files omega_p.txt and lambda_p.txt and they are stored in pairs. 

The file omega_p.txt contains p+1 pairs of numbers, which correspond to complex numbers omega_{p,j} for j=0,1,..,p

The file lambda_p.txt contains p pairs of numbers, which correspond to complex numbers lambda_{p,j} for j=1,..,p

In each pair, the first number represents the real part, and the second number represents the imaginary part ofthe corresponding complex coefficient.  

For example, the six numbers in the file omega_2.txt produce three complex numbers

omega_{2,0}=3.38017005528651915258863261823163476342019634e-1+i*4.90092790324733981473903274006328968202201367e-2                
omega_{2,1}=1.76038047397520510711626804982747033217784759e-1+i*9.14356948103534833324019951477784146473605287e-2                
omega_{2,2}=8.88987520697993788903818218401771554836540811e-3+i*3.04285009828797399426487016797075202811829613e-2 

Here we denoted by "i" the imaginary unit. 
  
The four numbers in the file lambda_2.txt produce two complex numbers

lambda_{2,1}=2.69164582091688009706339137658697227553732181e-1-i*2.12584884229293853002871808361074042130916306e-1               
lambda_{2,1}=5.44985588097650750556420472059131596464183711e-1-i*4.82555155741448361900427433254854630827531168e-1  

The backslash "\" is just the continuation line symbol (see MPFUN2020 documentation https://www.davidhbailey.com/dhbpapers/mpfun2020.pdf). 
For example, the first number in the file lambda_15.txt is written as

1.139422564909365885216557822615735135693580597482803103670775925826086082430798\
85995938659e-1       

and should be interpreted as 

1.13942256490936588521655782261573513569358059748280310367077592582608608243079885995938659e-1 
