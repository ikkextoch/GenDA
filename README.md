# GenDA
Genetic Data Analyser

This tools is a pipeline in which whole genome sequence data can be analysed. The functions for analysis are found in func_config.sh, while the pipeline itself can be found in GenDA.sh. User specific input can be entered in user_config.sh. GenDA.sh will source func_config.sh and func_config.sh will source user_config.sh.

Further input for GenDA consists of a tab delimited file with as content line seperated: [path to sample] [sample name]
