# DRNet
Codes for "Deep Concatenated Residual Network with Bidirectional LSTM for One-Hour-Ahead Wind Power Forecasting"  for Publication in IEEE Transactions on Sustainable Energy, 

### Authors
Min-seung Ko, Kwangsuk Lee, Jae-Kyeong Kim, Chang Woo Hong, Zhao Yang Dong, and Kyeon Hur
### Paper Information
https://ieeexplore.ieee.org/document/9290065
### Citation
M. -s. Ko, K. Lee, J. -K. Kim, C. W. Hong, Z. Y. Dong and K. Hur, "Deep Concatenated Residual Network with Bidirectional LSTM for One-Hour-Ahead Wind Power Forecasting," in IEEE Transactions on Sustainable Energy, doi: 10.1109/TSTE.2020.3043884.

### Datset
ERCOT Wind Power Dataset can be downloaded from http://www.ercot.com/gridinfo/generation
Jena's Temperature Dataset can be downloaded from https://www.kaggle.com/stytch16/jena-climate-2009-2016

### Experiments
Experiments for Wind Power Forecasting : ResNet_ERCOT.ipynb, MultiResidual_ERCOT.ipynb, MRN_7Layer_ERCOT.ipynb, MRN_11Layer_ERCOT.ipynb,  DenseNet_7Layer_ERCOT.ipynb, DenseNet_11Layer_ERCOT.ipynb, DRNet-3_7Layer_ERCOT.ipynb, DRNet3_11Layer_ERCOT.ipynb, DRNet-4_7Layer_ERCOT.ipynb, DRNet-4_11Layer_ERCOT.ipynb, Fused_DRNet-1_ERCOT.ipynb

Experiments for Attention & Weather : Weather_Fused.ipynb (w/o Attention, with Wind speed),  Weather_Attention_Fused_DRNet-1.ipynb (with Attention, Wind speed),  NotWeather_Fused.ipynb (w/o Attention, Wind speed),  Notweather_Attention_Fused.ipynb (with Attention, w/o Wind speed)

Experiments for Tempearture Forecasting : Jena_DRNet-3.ipynb, Jena_DenseNet.ipynb, Jena_FusedDRNet-1.ipynb, Jena_PureBi-LSTM.ipynb, Jena_ResNet.ipynb
