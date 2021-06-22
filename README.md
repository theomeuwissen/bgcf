# bgcf

Description of bgcf program is in paper Meuwissen, Van den Berg, Goddard (2021) GSE 53:19 (where the method was called BayesGC.

## Files:
bgcfx (linux executable)
bgcf.inp (example input file; contains also explanation of what the inputs should be)

## Not included files:
g.giv : lower triangle of inverse of GRM matrix in 3 columns: i j Ginv_value (only needed if Vu/=0.0)
dseed.rec : integer random seed of the random number generator (is overwritten on output)


## Output files:
bgcf.sol : contains SNPnumber and Nchains columns of solutions (mean and PESD (prediction error standardeviation)

bgcf.postpr : Nchain columns of posterior probabilities of the SNPs

bgcf.gebv : contains Nchain columns of total GEBV of the animals (mean and PESD)






## Questions
If something is not clear or there are problems Email me at : theo.meuwissen@nmbu.no





