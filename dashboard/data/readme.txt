rblw: Applied the formulas for rao-blackwellised shrinkage (which imply that the shrinkage target is of the form Tr(S)/p * I) 
however the derived shrinkage parameter was applied to the formula: delta*Prior_Cov + (1-delta)*S and Prior_Cov is:
Prior_Cov = [[mcr**2. 0], [0, mcr**2]] for mcr the mean cell radius

rblw_2: Prior_Cov is the one implied by the paper, ie Prior_Cov = Tr(S)/p*I