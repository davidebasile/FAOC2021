**EXPERIMENTS REPRODUCTION PACKAGE**

This repository contains the models and experiments logs for the article published at Formal Aspects of Computing 
https://doi.org/10.1007/s00165-021-00556-1

The model.xml contains the model, where all parameters for the set-ups are global, and comments on the queries of the verifier 
are available to improve readability. 

Since these comments are not readable by the command-line verifier, the set-up for experiments are in separate files, whose name 
indicate the specific set-up, among those used in the article, and the indication that these files have been used for the 
verifyta.exe command-line verifier of Uppaal. In all these set-ups the model is unchanged, but only the specific used parameters.

The experiments for the mitigated model, third setup, are also reported in a separate file.  In this case, the model has been amended 
as described in the article.

All logs of the execution of experiments are reported. 
Note that in such logs the probability uncertainty (epsilon) is, in some specific case, different from the one used in the article.
We also archived the executable of the used verifier for reproducibility of the logs. 

A legacy file "model with occ and mitigation.xml" is stored, not useful for reproducibility.
