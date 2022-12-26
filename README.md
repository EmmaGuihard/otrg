# otrg

Code for the paper [**Entropic Optimal Transport in Random Graphs**](https://arxiv.org/abs/2201.03949).

## Fork for paper review

*Jérémie Dentan, Emma Guihard.*

To reproduce our figures, please use Python 3.0 and install dependencies in `requirements.txt`. Then, run the following:

### Figure 2

* Line 33 of script `local_kernels_tube.py`, set `use_bridge_manifold`to `True`.
* Run `python local_kernels_tube.py`
