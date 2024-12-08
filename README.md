# ADLfinal
A repo for the Advanced Deep Learning Project: note that most of this code is adapted from https://github.com/kmeng01/rome 
More information about the parent project can be found there. 
Also visit https://rome.baulab.info/ for more information about this project and the paper written about it (Ref: Kevin Meng, David Bau, Alex Andonian, and Yonatan Belinkov. "Locating and Editing Factual Associations in GPT." Advances in Neural Information Processing Systems 36 (2022).)

There are two branches called 'replication' and 'math'. 

'replication' contains the code from the parent repository slightly changed to run on gpt2-medium per default. 
'math' contains the code for a modified application of the suggested methods to run causal tracing and rank-one model editing on a gpt2-medium based model fine tuned on elementary school math questions 

results can be found in the following jupyter notebooks in the notebooks folder: 
- causal_trace.ipynb
- average_causal_effects.ipynb
- medium_fine_tune_math_hpo_final.ipynb
- rome.ipynb 
