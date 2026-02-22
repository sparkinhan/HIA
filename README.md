# HIA
This repository is the official implementation of the AAAI 2026 paper: [Multi-granularity Interactive Attention Framework for Residual Hierarchical Pronunciation Assessment](You can run below command on your virtual environment).

# Dataset
An open source dataset, SpeechOcean762 (licenced with CC BY 4.0) is used. You can download it from https://www.openslr.org/101.

# Requisites
You can set up virtual environment by below command
  * pip install -r requirements.txt

# Training
This bash script will run each model 5 times.
  * cd src
  * bash run_hipama.sh
    
Due to the random elements, </strong>every run does not produce the same results</strong>.

The reported results in the paper are the averages of the final epoch results for five different seeds.
