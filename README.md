# Online learning of the transfer matrix of dynamic scattering media
Codes to simulate wavefront shaping experiments and optimally recover the transfer matrix of dynamic scattering media in an online and recursive fashion.

Its use in a conventional wavefront shaping experiment is illustrated in the figure below.


<img src="https://github.com/laboGigan/online_learning_TM/blob/main/pics/method_summary.png" width="48"/>


The core of the process lies in the so-called Recursive Least-Squares (RLS) algorithm, described in pseudo-code below.


![alt text](https://github.com/laboGigan/online_learning_TM/blob/main/pics/algo.png "summary")
