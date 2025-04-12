# SpectralTrain
This is the source code for the paper titled 'SpectralTrain: A Universal Framework for Hyperspectral Image Classification'.

### 1. Setup Environment
```bash
conda create -n spectraltrain python=3.10
conda activate spectraltrain
pip install -r requirements.txt

All experiments were performed using PyTorch 2.1.2, along with TorchVision 0.16.2 and TorchAudio 2.1.2, under CUDA 12.1 and Python 3.10. The hardware platform was a high-performance workstation equipped with an Intel Core i7-13700 CPU (16 threads), 32 GB RAM, and an NVIDIA RTX 4090D GPU with 24 GB VRAM. Data preprocessing and caching were supported by a 50 GB NVMe SSD, ensuring efficient disk I/O and minimal data-loading latency.

Code will be released soon.
