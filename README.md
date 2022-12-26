# otrg

Code for the paper [**Entropic Optimal Transport in Random Graphs**](https://arxiv.org/abs/2201.03949).

## Fork for paper review

*Jérémie Dentan, Emma Guihard.*

To reproduce our figures, please use Python 3.0 and install dependencies in `requirements.txt`. Then, run the following:

### Figure 2

* Line 33 of script `local_kernels_tube.py`, set `use_bridge_manifold`to `True`.
* Run `python local_kernels_tube.py`

### Figure 3

* Line 33 of script 'local_kernels_tube.py', set 'use_bridge_manifold' to 'False'.
* Line 56 of script 'local_kernels_tube.py', different values of n, the value n=3000 is displayed.
* Run 'python local_kernels_tube.py'

### Figure 4

* Line 33 of script 'local_kernels_tube.py', set 'use_bridge_manifold' to 'False'.
* Line 56 of script 'local_kernels_tube.py', different values of n, the value n=100 is displayed.
* Line 89 of script 'utils/data.py' (function connected_eps_graph), set h=n**(-1/3).
* Line 92 of script 'utils/data.py' (function connected_eps_graph), set h*=10.
* Run 'python local_kernels_tube.py'

### Figure 5

* Line 33 of script 'local_kernels_tube.py', set 'use_bridge_manifold' to 'False'.
* Line 56 of script 'local_kernels_tube.py', different values of n, the value n=200 is displayed.
* Line 89 of script 'utils/data.py' (function connected_eps_graph), set h=n**(-1/3).
* Line 92 of script 'utils/data.py' (function connected_eps_graph), set h*=5.
* Run 'python local_kernels_tube.py'
