# Readme
This repository contains the data from the paper "Gravitational Waves from Primordial Black Holes formed by Null Energy Condition Violation during Inflation" (arxiv.org/abs/2602.16292). We have open-sourced the stochastic gravitational wave background (SGWB) energy spectrum data for the ringdown phase during the formation of primordial black holes (PBHs) (folder: PBH ringdown), as well as the energy spectrum data for the GW emissions from PBH binary mergers (folder: PBH merge), as shown in Figure 2 of the paper. The 'Blue' and 'Orange' in the data filenames correspond to different parameter benchmark points in the paper.

## PBH ringdown

In the PBHringdown folder, the filenames correspond to the data tables of GW emissions from the ringdown phase for different parameter benchmark points (e.g., Blue and Orange). Each table is in .csv format and includes the header Frequency (Hz),OmegaGW. The corresponding data structure is: {{$f_0$, $\Omega_0$}, ..., {$f_n$, $\Omega_n$}}, where $f$ and $\Omega$ represent the observed frequency of the gravitational waves (in Hz) and the logarithmic value of the corresponding GW energy density fraction $\log_{10}\Omega_{\text{GW}}h^2$, respectively.

## PBH merge

In the merge folder, the filenames correspond to the data tables of GW emissions from PBH binary mergers for different parameter benchmark points (e.g., Blue and Orange). Each table is also in .csv format and includes the header Frequency (Hz),OmegaGW. The corresponding data structure is as follows: {{$f_0$, $\Omega_0$}, ..., {$f_n$, $\Omega_n$}}, where $f$ and $\Omega$ represent the observed frequency of the gravitational waves (in Hz) and the logarithmic value of the corresponding GW energy density fraction $\log_{10}\Omega_{\text{GW}}h^2$, respectively.

If you have any questions or are interested in related fields, please contact caiyong@zzu.edu.cn.
