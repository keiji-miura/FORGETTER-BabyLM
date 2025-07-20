# FORGETTER-BabyLM: 

The results (validated losses of next token prediction task) for training minGemma models with BabyLM10M or BabyLM100M dataset by using normal or FORGETTER learning algorithm.

Three major premises: "Input token length = 512", "GPT2 Tokenizer", "No drop-out"



## Installation:
conda create -n minGemma python=3.11  
conda activate minGemma  
conda install pytorch==2.2.2 torchvision==0.17.2 torchaudio==2.2.2 pytorch-cuda=11.8 -c pytorch -c nvidia  

## Special requirements:
pip install accelerate>=0.26.0  
pip install "numpy<2"

