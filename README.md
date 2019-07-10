# MaMIMO_IndoorExperiment
This repository includes Matlab scripts to process the uplink channel data collected in an indoor experiment using KULeuven Massive MIMO testbed.

Authors: Cheng-Ming Chen, Andrea P. Guevara. 2019

## Instructions

1. Download the data set to be proccesed. <br>
Data Set: https://owncloud.esat.kuleuven.be/index.php/s/oYepckKfoJj93BC  <br>

2. Open the required .m file according the specific scenario (collocated or distributed) detailed here: <br>

3. Each .m file loads a matrix H variable which contains the channel collected for the specific scenario. This matrix 

The configuration of the matrix H variable is [Antennas,Symbols,Subcarriers,User].

3. This dataset is opened to the academic community for research. If the data is used in your publication, please cite our paper as follows: <br>

https://ieeexplore.ieee.org/document/8335182  <br>

@inproceedings{chen2019experimental, <br>
  title={Experimental Study of User Selection for Dense Indoor Massive MIMO}, <br>
  author={Chen, Cheng-Ming and Wang, Qing and Guevara Toledo, Andrea and Pollin, Sofie}, <br>
  booktitle={IEEE Infocom 2019}, <br>
  year={2019}, <br>
  }


Note: The Matlab scripts in this repository will work only for the previous data set.

## Contact
If you have any question or problem you can always contact us: <br>

Andrea P. Guevara: aguevara@esat.kuleuven.be <br>
Cheng-Ming Chen: cchen@esat.kuleuven.be


## Acknowledgment

This work was funded by the European Union's Horizon 2020 under grant agreement no. 732174 (ORCA project).
