[![DOI](https://zenodo.org/badge/197470755.svg)](https://zenodo.org/badge/latestdoi/197470755)
# Python Scripts for Wind Turbine Main Bearing Fatigue Life Estimation with Physics-informed Neural Networks

This repository is provided for replication of results presented in:
- Y. A. Yucesan and F. A. C. Viana, "[A physics-informed neural network for wind turbine main bearing fatigue](http://www.phmsociety.org/node/2736)," International Journal of Prognostics and Health Management, Vol. 11 (1), 2020. (ISSN: 2153-2648).

- Y. A. Yucesan and F. A. C. Viana, "[A hybrid model for main bearing fatigue prognosis based on physics and machine learning](https://arc.aiaa.org/doi/abs/10.2514/6.2020-1412)," AIAA SciTech Forum, Orlando, USA, January 6-10, 2020, AIAA 2020-1412 (DOI: 10.2514/6.2020-1412).

- Y. A. Yucesan and F. A. C. Viana, "[Wind turbine main bearing fatigue life estimation with physics-informed neural networks](http://phmpapers.org/index.php/phmconf/article/view/807)," Proceedings of the Annual Conference of the PHM Society, Vol. 11 (1), Scottsdale, USA, September 21-26, 2019 (DOI:10.36001/phmconf.2019.v11i1.807).

This repository includes two sets of the code.

**Basic:**
- run01 file trains the RNN using pretrained MLP model with fixed initial weights.
- run02 file predicts the fatigue damage accumulation of the wind turbine main bearing for 6 months.

**Advanced:**
- run01 file generates a random plane approximation for MLP training.
- run02 file trains the MLP with randomly generated initial weights.
- run03 file trains the RNN using trained MLP model.
- run04 file predicts the fatigue damage accumulation of the wind turbine main bearing for 30 years.

In order to run the codes, you will also need to:
1. Install the PINN python package: https://github.com/PML-UCF/pinn
2. Download the data:
Yucesan, Yigit, 2019, "Wind Turbine Main Bearing Fatigue Life Prediction with PINN" (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/ENNXLZ), Harvard Dataverse, V1, UNF:6:o3b2Pkuz0uIgkQ57jEKGOA== [fileUNF]
and extract folders inside wind_bearing_dataset to the directory where this repository is cloned.

## Citing this repository

Please, cite this repository using: 

    @misc{2019_yucesan_viana_python_main_bearing,
        author    = {Y. A. Yucesan and F. A. C. Viana},
        title     = {Python Scripts for Wind Turbine Main Bearing Fatigue Life Estimation with Physics-informed Neural Networks},
        month     = Aug,
        year      = 2019,
        doi       = {10.5281/zenodo.3355725},
        version   = {0.0.1},
        publisher = {Zenodo},
        url       = {https://github.com/PML-UCF/pinn_wind_bearing}
        }
The corresponding reference entry should look like:

Y. A. Yucesan and F. A. C. Viana, Python Scripts for Wind Turbine Main Bearing Fatigue Life Estimation with Physics-informed Neural Networks, v0.0.1, Zenodo, https://github.com/PML-UCF/pinn_wind_bearing, doi:10.5281/zenodo.3355725.
