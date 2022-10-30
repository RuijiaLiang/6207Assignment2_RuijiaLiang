# 6207Assignment2_RuijiaLiang

# Workflow
1.Load the data into R and cleaning the data to do some preparation for analysis.
2.Use the small set of data from Clark et al. (2020) to get some statistics for further analysis.
3.Merge the statsitics with the big dataset ocean_meta_data.csv.
4.Calculate the lnRR and fit to the right model. Summarize it.
5.Use funnel plot to visualize the file-drawer bias. Use time-lag plot to visualize the time lag bias.
6.Fit the data to MLMR to quantify the the file-drawer bias, the time lag bias and the IF bias.
7.Discuss and summarize the potential fo publication bias and find out which studies contribute more to the bias.

# File structure of the write-out file
Column heading:Description
Study:Code for each individual study
Authors:Authors of each paper
Year (online):Year the final paper was made available online
Year (print):Year the final paper was included in a journal volume/issue
Title:Title of each paper
Journal:Journal the paper was published in
Pub year IF:The journal impact factor for the year the paper was published; obtained from InCites Journal Citation Reports
2017 IF:The journal impact factor for 2017 (i.e., most recent journal impact factor); obtained from InCites Journal Citation Reports
Average n:Average sample size for the study; average of indiviudal sample sizes for the contol and experimental groups
Effect type:The type of effect concluded by the study regarding the effect of OA on behaviour; strong, weak, or no effect (see Supplementary Methods for details)
Species:The species used in each individual experiment
Climate (FishBase):Climatic region for each species; obtained from FishBase
Env cue/stimulus?:Whether or not the experiment included a cue or stimulus in the experiment (olfactory, visual, auditory, or physical)
Cue/stimulus type:The type of cue or stimulus used
Behavioural metric:The specific measure of behaviour tested
Life stage:Life stage of the fish tested
ctrl.n:Sample size of the control group
ctrl.mean:Mean of the control group
ctrl.var:Measured variance of the control group
ctrl.vartype:The metric of variance used for the control group (standared deviation, standard error, 95% confidence interval, or inter-quartile range
ctrl.sd:The standard deviation of the control group, calculated from ctrl.vartype
oa.n:Sample size of the experimental group
oa.mean:Mean of the experimental group
oa.var:Measured variance of the experimental group
oa.vartype:The metric of variance used for the experimental group (standared deviation, standard error, 95% confidence interval, or inter-quartile range
oa.sd:The standard deviation of the experimental group, calculated from ctrl.vartype
lnRR:Raw effect size (natural log transformed response ratio)
|lnRR|:Absolute effect size (natural log transformed response ratio)
Weighted mean |lnRR|:The mean effect size for each study computed as the average of |lnRR| measurements for a given study

# History
25/10/2022  load the data into R
25/10/2022  finish preparation steps
25/10/2022  generate the summary statistics
25/10/2022  merge the data frames
25/10/2022  calculate the lnRR effect size
25/10/2022  fit the model
30/10/2022  interpret the model
30/10/2022  finish MLMR
30/10/2022  determine the potential for publication bias and which studies contribute most to the publication bias

ALL DONE!(30/10/2022,23:25)
