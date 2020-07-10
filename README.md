# SINEsuppl
### This page contains supplementary data for the manuscript
## *"Search for SINE repeats in the rice genome using correlation-based positional weight matrices."*
## Yulia M. Suvorova, Anastasia M. Kamionskaya, Eugene V. Korotkov

### Rice genome analysis

All coordinates presented in tsv format (Chromosome, Begin, End, SineFamilyId, Score, Strand)

- RepeatMasker initial dataset (coordinates of 16421 copies) **O_sativa_RM_160.bed.total.gz**
- HDRSM initial dataset  (coordinates of 40415 copies)  **total_sine_sorted.bed.gz**
- RepeatMasker the final set (coordinates of 14712 copies)  **O_sativa_RM_160_overlap20_uniqid_noDUST.bed.gz**
- HDRSM the final set (coordinates of 15423 copies) **total_overlap20_uniqid_noDUST.bed.gz**


### Simulated dataset analysis 
 Datasets include fasta sequences of simulated chromosomes (\*.fa) and coordinates of inserted SINEs in these sequences (\*.tsv) 
 
- Sequence *FullLengthSet* <a href="/sinesuppl/files/TrunkatedSet.tar.gz">(archive.tar.gz)<a></p>
- Sequence *TruncatedSet* <a href="/sinesuppl/files/FullLengthSet.tar.gz">(archive.tar.gz)<a></p>

#### Results obtained on the simulated datasets

- Repeatamsker results obtained on FullLengthSet (**RepeatMasker_FullLengthSet.tsv.gz**) and TrunkatedSet (**HDRSM_TrunkatedSet.tsv.gz**).
- HDRSM results obtained on FullLengthSet (**HDRSM_FullLengthSet.tsv.gz**) and TrunkatedSet (**HDRSM_TrunkatedSet.tsv.gz**). HDRSM sets include results obtained with different *Kd* values (0.0, -0.5, -1.0, -1.5 and -2.0).

### Executable files 

Executable files for the HDRSM method can be found here exe_files.tar.gz



<p> With any questions about the data, please contact Yulia Suvorova (<i>suvorovay@gmail.com</i>) </p>

