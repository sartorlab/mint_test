# Purpose

This repository stores data used to test the mint methylation pipeline: <https://github.com/sartorlab/mint>.

## Types of test data

### Hybrid

Based on [GSE52945](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE52945), which is a hybrid of RRBS and hMe-Seal data. The test data were created by running full mint analysis on IDH2mut_1 and IDH2mut_2 versus NBM_1 and NBM_2 samples, and then backwards selecting the reads. Reads from the following region were selected to represent a variety of end results.

* chr1:2209176-2214175 (hyper_mc_hyper_hmc)
* chr2:71942840-72005839 (hypo_mc_hyper_hmc)
* chr7:36074781-36102780 (hyper_hmc)
* chr8:35090385-35095384 (hyper_mc)
* chr11:67384075-67389174 (hypo_mc_hypo_hmc)
* chr16:3046564-3096563 (hyper_mc_hyper_hmc and hyper_mc_hyper_hmc)
* chr19:39702429-39752428 (hyper_mc_hypo_hmc)

### Pulldown

This data is going to be based on IP methods measuring 5mC and 5hmC.

## Test data mappings

```
bisulfite_samples:
    IDH2mut_1_errbs : 6000
    IDH2mut_2_errbs : 6001
    NBM_1_errbs : 6002
    NBM_2_errbs : 6003
```

```
pulldown_samples:
    IDH2mut_1_hmeseal : 7000
    IDH2mut_2_hmeseal : 7001
    NBM_1_hmeseal : 7002
    NBM_2_hmeseal : 7003
    IDH2mut_1_hmeseal_input : 7004
    IDH2mut_2_hmeseal_input : 7005
    NBM_1_hmeseal_input : 7006
    NBM_2_hmeseal_input : 7007
```
