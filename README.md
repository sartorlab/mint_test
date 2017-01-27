# Purpose

This repository stores data used to test the mint methylation pipeline: <https://github.com/sartorlab/mint>.

## Types of test data

### Hybrid

Based on [GSE52945](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE52945), which is a hybrid of RRBS and hMe-Seal data. The test data were created by running full mint analysis on IDH2mut_1 and IDH2mut_2 versus NBM_1 and NBM_2 samples, and then backwards selecting the reads. Reads from the following region were selected to represent a variety of end results.

- chr1:2220910-2270909 (hyper_mc_hyper_hmc)
- chr16:3046564-3096563 (hyper_mc_hyper_hmc)
- chr11:67046158-67096157 (hypo_mc_hypo_hmc)
- chr2:71942840-72005839 (hypo_mc_hyper_hmc)
- chr19:39702429-39752428 (hyper_mc_hypo_hmc)
- chr7:36074781-36102780 (hyper_hmc)
- chr8:35090385-35095384 (hyper_mc)

### Pulldown

This data is going to be based on IP methods measuring 5mC and 5hmC.
