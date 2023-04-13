# FedDWA

This repository contains the offical code for FedDWA. 


## Instructions
This project uses Python 3.8.10 and PyTorch 1.10.0.

### Data:
1. Download the [PACS](https://drive.google.com/uc?id=1JFr8f805nMUelQWWmfnJR3y4_SYoN5Pd) (Li et al., 2017), [VLCS](https://drive.google.com/uc?id=1skwblH1_okBwxWxmRsp9_qi15hyPpxg8) (Fang et al., 2013) and [Office-Home](https://drive.google.com/file/d/0B81rNlvomiwed0V1YUxQdC1uOTg) (Venkateswara et al., 2017) datasets and put them in `data/raw/`.
2. Resize images and generate training, validation and test splits. Run `./00_prepare_data.sh` after installing the project environment (instructions below).


### Project environment:
1. Create and activate virtual environment: 1) `python3 -m venv env`, 2) `source env/bin/activate`
2. Install required packages: `pip install -r requirements.txt`
3. Install project modules (src): `pip install -e .`
