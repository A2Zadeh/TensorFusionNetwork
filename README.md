# The code will no longer be maintained in this repository. Please refer to CMU-Multimodal Data SDK under models folder to find the newest implementations for Tensor Fusion Network. 

# TensorFusionNetwork
This is the code for [Tensor Fusion Network for Multimodal Sentiment Analysis](http://aclweb.org/anthology/D17-1115) published in EMNLP 2017 and orally presented in multimodal session. The code is quite straight forward. Please download the CMU-MOSI dataset using [CMU Multimodal Data SDK](https://github.com/A2Zadeh/CMU-MultimodalDataSDK) or [my website](https://www.amir-zadeh.com/mosi-eula). The data_loader.py helps you load the data in the correct format, however I suggest using the CMU Multimodal Data SDK for better loading as the directory structure of CMU-MOSI changes when we add new features. The code for the algorithm is in tf_mosi.py.  


Please cite the following publication if you are using this code:

```
@inproceedings{tensoremnlp17,
title={Tensor Fusion Network for Multimodal Sentiment Analysis},
author={Zadeh, Amir and Chen, Minghai and Poria, Soujanya and Cambria, Erik and Morency, Louis-Philippe},
booktitle={Empirical Methods in Natural Language Processing, EMNLP},
year={2017}
}
```
