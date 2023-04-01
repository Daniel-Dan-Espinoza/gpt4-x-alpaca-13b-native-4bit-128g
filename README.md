GPTQ 4bit quantization of: https://huggingface.co/chavinlo/gpt4-x-alpaca

Command: 
CUDA_VISIBLE_DEVICES=0 python llama.py ./models/chavinlo-gpt4-x-alpaca
--wbits 4 
--true-sequential 
--act-order 
--groupsize 128 
--save gpt-x-alpaca-13b-native-4bit-128g.pt
