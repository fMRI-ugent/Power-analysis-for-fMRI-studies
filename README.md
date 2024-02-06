# Power-analysis-for-fMRI-studies
Here, you can find useful materials and links to conduct power analyses and calculate sample sizes for fMRI studies.

## Let's start with some relevant papers:
- [How many participants do we have to include in properly powered experiments? A tutorial of power analysis with reference tables (M. Brysbaert 2019)](https://www.journalofcognition.org/articles/10.5334/joc.72/)
- A power calculation guide for fMRI studies (J. Mumford 2012): https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3427872/
- Sample size evolution in neuroimaging research: An evaluation of highly-cited studies (1990–2012) and of latest practices (2017–2018) in high-impact journals: https://www.sciencedirect.com/science/article/pii/S1053811920306509
- Small sample sizes reduce the replicability of task-based fMRI studies (Turner et al., 2018): https://www.nature.com/articles/s42003-018-0073-z
- fMRI replicability depends upon sufficient individual-level data (Derek Evan Nee, 2019): https://www.nature.com/articles/s42003-019-0378-6
- Reply to: fMRI replicability depends upon sufficient individual-level data (Turner et al., 2019): https://www.nature.com/articles/s42003-019-0379-5
- http://www.dovepress.com/getfile.php?fileID=12772 
- An empirical investigation into the number of subjects required for an event-related fMRI study (Murphy and Garavan 2004): https://www.sciencedirect.com/science/article/abs/pii/S1053811904000977?via%3Dihub





#### Before to start let's install dcm2bids and its dependencies
[Here](https://unfmontreal.github.io/Dcm2Bids/docs/get-started/install/) all the instruction to install dcm2bids and its dependencies.

After following the instructions you arrive to the last 2 steps (run in the terminal):
1. Activate dcm2bids
```diff
@@ conda activate dcm2bids @@
```
3. Verify that dcm2bids works
```diff
@@ dcm2bids --help @@
```
