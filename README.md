# MULTI-MODAL-THREAT-DETECTION-FOR-SURVEILLANCE-SYSTEM

## Requirements
* This code is tested with Keras 2.2.4, Tensorflow 1.13, CUDA 9.0, on a machine  running on Ubuntu or any debian based operating system.
* Other packages needed `keras pillow matplotlib scikit-learn scikit-image opencv-python pydot` and `GraphViz`.
* Minimum hardware tested on for inference NVIDIA GeForce MX150 (laptop) / NVIDIA GeForce GTX 950 (desktop).

## Testing 
  * Run `python monodepth/run.py --video monodepth/examples/ll.mp4`.
  
## Insatallation
* Run `./install-pre.sh` to install all the prerequisites.
* Run `./install.sh` to install the program to the home directory.
* To execute the program run `run` along with the aruments.



## Training
* Run `python monodepth/train.py --data all --gpus 4 --bs 8`.
