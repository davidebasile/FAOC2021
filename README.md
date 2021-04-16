EXPERIMENTS REPRODUCTION PACKAGE

This repository contains the models and experiments log for the article submitted at Formal Aspects of Computing, special issue 
of our RSSRail 2019 paper. 
The model.xml contains the model, where all parameters for the set-ups are global, and comments on the queries of the verifier 
are available to improve readability. 
Since these comments are not readable by the command-line verifier, the set-up for experiments are in separate files, whose name 
indicate the specific set-up, among those used in the article, and the indication that these files have been used for the 
verifyta.exe command-line verifier of Uppaal. 
The experiments for the mitigated model, third setup, are also reported in a separate files. 
All logs of the execution of experiments are reported. 
Note that the probability uncertainty is set to 0.05 in the logs, whilst in the article sometimes has been set to 0.005.
A legacy file "model with occ and mitigation.xml" is stored, that basically contains old comments.
We also archived the executable of the used verifier for reproducibility. 
New versions of the verifier are available at the Uppaal site.
