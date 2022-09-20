# CMSC423_F22_Project1_sample_data

The file names encode the parameters used.  Specifically, to generate `reads_100_5_0.30.fa` (and the corresponding `.stats`), the simulator was run on `genome.fa` with read length 100, expected coverage 5, 
and $\theta = 0.3$.  To reconstruct `recon_100_5_0.30.fa` the assmebler was run with the input set of reads and min overlap of 30.

To generate `reads_200_40_0.20.fa` (and the corresponding `.stats`), the simulator was run on `genome_small.fa` with read length 200, expected coverage 40, 
and $\theta = 0.2$.  To reconstruct `recon_small_200_40_0.20.fa` the assmebler was run with the input set of reads and min overlap of 40 (i.e. $\theta * 200$).

