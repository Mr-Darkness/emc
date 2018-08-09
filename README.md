# emc
Efficient and Effective Algorithms for Maximum Consensus Robust Fitting

This code is used to reproduce the results in "Wen, Ying, Liu, Qiu, Efficient and Effective Algorithms for Maximum Consensus Robust Fitting, 2018". 

To use the code, firstly unzip 'src.zip'.

This code is modified from the code of Huu Le at https://www.researchgate.net/publication/320707327demo_pami, details please see the paper "H. Le, T. J. Chin, A. Eriksson, and D. Suter, “Deterministic approx-imate methods for maximum consensus robust fitting,” arXiv preprint, arXiv:1710.10003, 2017."

Note that, some codes of Huu Le are directly coped here from https://www.researchgate.net/publication/320707327demo_pami to facilitate the ease of use for interested readers who want to reproducing the results in our paper. The coped codes (contained in the '/src' folder) include the EP method, RANSAC method and their dependency. We copy them here only for academic use purpose to illustrate the comparison results of the algorithms in our paper.

SeDuMi is need in solving the LP problems, which is available at http://sedumi.ie.lehigh.edu/, we used SeDuMi 1.3.