# tensorflow

## Installation

### Python instalation

    sudo apt install python-is-python3

### Tenrsorflow installation

    pip install     tensorflow-cpu

### Cuda installation

    wget https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/cuda-ubuntu2004.pin
    
    sudo mv cuda-ubuntu2004.pin /etc/apt/preferences.d/cuda-repository-pin-600
    
    wget https://developer.download.nvidia.com/compute/cuda/11.0.3/local_installers/cuda-repo-ubuntu2004-11-0-local_11.0.3-450.51.06-1_amd64.deb
    
    sudo dpkg -i cuda-repo-ubuntu2004-11-0-local_11.0.3-450.51.06-1_amd64.deb
    
    sudo apt-key add /var/cuda-repo-ubuntu2004-11-0-local/7fa2af80.pub
    
    sudo apt-get update
    
    sudo apt-get install cuda

