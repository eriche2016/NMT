# NMT
Implementation of global attention in torch

Train a model from scratch, (settings can be modified in doall.lua)

th doall.lua

Load a model and test it, 

th doall.lua -train 0 -pretrained_model ./model/nEpoch_16_05_13_2016_00_07_16.net -ans_path ./translation_test.txt 

Evaluate it with BLEU 

python bleu.py ./translation_test.txt ./data/test.tgt 

