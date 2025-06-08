### Project Data for the VIP HPC Project, Fall 2024 (Spring 2025)
 ----------------------------------------------------
 ## Description
In this repo, you will find results for quantum machine learning (QML) using HPC computing resources provided by the NYU VIP HPC team, guided by Dr. Zongrui Pei.

For much of the material in this repository, we referenced IBM Qiskit's [machine learning tutorials](https://qiskit-community.github.io/qiskit-machine-learning/)

Note that the time of the experiment, the Qiskit machine learning tutorial was on version 0.7.9

Our latest code base used for publication has been improved and reorganized by Dr. Yilun Gong here:
https://github.com/gongyilun/QMML_SFE_Mg

(the following descriptions might be outdated)
Our exploration concerns with prediction of stacking fault energies (SFE) of elements based on their physical properties: electron negativity, bulk modulus, and volume in cubic angstrom. We tried two existing Qiskit quantum machine learning algorithms: QVSR and VQR, and recorded the average test accuracy under different hyperparameter settings. 

The details for each method can be found in the sub folders, and the average test accuracy will be included in 'accuracy.csv'.


## Acknowledgement
 - Dr. Zongrui Pei revised my earlier code and made cricual corrections. 

 - Dr. Yilun Gong streamlined the testing process and also made corrections.

 - Dan Zhang assisted to obtain the result and graphs of the earlier versions of the QNN code.

 - Daniel Lee helped reviewing earlier versions and offered suggestions of improvement.

Their contributions to this project are tremendous. I also learned greatly from these encouraging individuals, some being mentors, and others are my classmates. I also want to thank the NYU HPC team for their professionalism and timely response, provding us with a trouble-free environment to conduct our research. We hope this project could offer value to those who have interest in machine learning or quantum computing, and also have a background in material science. Our code may also serve as starter templates to save time for researchers.
