# README

This repository contains the data from the paper "Gravitational Waves from Primordial Black Holes formed by Null Energy Condition Violation during Inflation" (arxiv.org/abs/2602.16292). We have open-sourced the stochastic gravitational wave background (SGWB) energy spectrum data for the ringdown phase during the formation of primordial black holes (PBHs) (folder: PBH ringdown), as well as the energy spectrum data for the GW emissions from PBH binary mergers (folder: PBHs merge), as shown in Figure 2 of the paper.

## PBH ringdown

In the PBHringdown folder, the filenames are formatted as OmegaGW_sPBH_<Color>.csv (e.g., OmegaGW_sPBH_Blue.csv), where <Color> corresponds to the parameter benchmark points used in the paper. Each table is in .csv format and includes the header Frequency (Hz),OmegaGW. The corresponding data structure is: {{$f_0$, $\Omega_0$}, ..., {$f_n$, $\Omega_n$}}, where $f$ and $\Omega$ represent the observed frequency of the gravitational waves (in Hz) and the logarithmic value of the corresponding GW energy density fraction $\log_{10}\Omega_{\text{GW}}h^2$, respectively.

## PBHs merge

In the merge folder, the filenames are formatted as OmegaGW_merge_<Color>.csv (e.g., OmegaGW_merge_Blue.csv), where <Color> corresponds to the parameter benchmark points used in the paper. Each table is also in .csv format and includes the header Frequency (Hz),OmegaGW. The corresponding data structure is as follows: {{$f_0$, $\Omega_0$}, ..., {$f_n$, $\Omega_n$}}, where $f$ and $\Omega$ represent the observed frequency of the gravitational waves (in Hz) and the logarithmic value of the corresponding GW energy density fraction $\log_{10}\Omega_{\text{GW}}h^2$, respectively.

If you have any questions or are interested in related fields, please contact caiyong@zzu.edu.cn.
