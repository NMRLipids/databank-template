# Description

Pressure-area isotherm correction notebook demonstrates, how the monolayer simulation set conducted at different area-per-lipid (ApL) values
allow us to correct experimental pressure-area isotherm if the XRR profile is available for a given lateral pressure value. Here we need free data sources:
1. XRR profile recorded for known lateral pressure;
2. Pressure-area isotherm measured at the same temperature;
3. The set of simulations conducted at the same conditions at different area-per-lipid values.

Corresponding simulations of M.Javanainen (https://doi.org/MJ_DPPC_10.1021/acs.langmuir.7b02855), are already deposited into the cited repository and the electron density distribution along the monolayer normal is already precomputed there.

In the notebook, we demonstrate, how to correct pressure-area isotherm (1) by using a reference XRR profile (2) and set of electron density profiles simulated at different ApL values (3). All three sets of data is pre-loaded into NMRlipids Databank monolayer development fork.

# Requirements

1. Folder `./Databank-monolayers` should be initialized by *NMRlipids/Databank@monolayer-dev* from one of the sources
    - https://github.com/fsuarezleston/NMRLipids_Databank/tree/monolayer-dev
    - https://github.com/comcon1/Databank/tree/monolayer-dev
2. Please make your python environment to satisfy NMRLipids Databank requirements. We don't have any additional requirements inside this notebook.

# Authors
- Fabián Suárez Lestón (Universidade de Santiago de Compostela)
  [email:fabian.suarez.leston@usc.es]
- Markus S. Miettinen (University of Bergen, Computational Biology Unit)
  [email:markus.miettinen@uib.no]
- Alexey M. Nesterenko (University of Bergen, Computational Biology Unit)
  [email:comcon1@protonmail.com]
