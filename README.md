# MiN
Public code for MiN

# How to run
1. You need download all six datasets firstly and then revise the [DATA-PATH] in *data_process/data.py*. Finally, you can run the *run.sh* to reproduce the main results (10 steps) for MiN.

2. If the pre-trained weight file for ViT-B/16-in21k cannot be download automatically, please manually download it and revise the load manner in *backbones/pretrained_backbone.py*

3. If you want to run MiN with ViT-B/16-in1k, please download the corresponding pre-trained weight file from Huggingface.

4. Any other settings for CIL can be operated by revising *configs/base_configs/[DATASETS_NAME].json*. Hyperparameters can be revised in *configs/model_configs/MiN.json*



