# COLD
Algorithm for COntinuous monitoring of Land Disturbance (COLD) using Landsat time series. It can detect many kinds of land disturbance continuously as new images are collected and provide historical land disturbance maps retrospectively.
Please contact Zhe Zhu (zhe@uconn.edu) at Department of Natural Resources and the Environment, University of Connecticut if you have any questions.

To stack the Landsat data into BIP format as the the input of the COLD algorithem, please check out the **autoPrepareDataARD.m** (if Landsat ARD) or **autoPrepareDataESPA.m** (if ESPA surface reflectance) in the [CCDC package](https://github.com/GERSL/CCDC).

If no full MATLAB licenses, you may run **scanRequiredToolboxes.m** for displaying a list of all Matlab toolboxes that are required for executing this algorithm.

**Reference dataset** are available at [this Google Drive](https://drive.google.com/file/d/1y53vCqY_K9W7R7jONFT6iI-FyH2tz_gR/view?usp=sharing), which include the reference data created by [TimeSync](https://timesync.forestry.oregonstate.edu) as well as the time series of Landsat surface and TOA reflectance.

Please cite the following paper:
Zhu, Z., Zhang, J., Yang, Z., Aljaddani, A.H., Cohen, W.B., Qiu, S. and Zhou, C., Continuous monitoring of land disturbance based on Landsat time series. Remote Sensing of Environment (2019). https://doi.org/10.1016/j.rse.2019.03.009
