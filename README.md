# singularity_deep_learning_gpu_centos7_x86_64
Singularity container recipe for Deep Learning with GPU for architecture x86_64 based on a CentOS 7. In the specific:  

- centOS 7 with cuda library (10.0-devel-centos7) 
- GNU compiler 7 
- Python 3.6 
- OpenMPI 2.1.1 (compiled with support for psm2, pmix, verbs) 
- Tensorflow 1.14.0 GPU (pip) 
- Py-Torch 1.4.0 GPU (pip) 
- Torchvision 0.5.0 CPU (pip) 
- MxNet 1.5.1 CPU (pip) 
- Horovod 0.19.1 (compiled with Tensorflow, Pytorch, MxNet) 

This recipe works on in the Cineca cluster (arch x86_64): 

- Galileo
