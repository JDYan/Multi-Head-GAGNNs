Modeling Spatio-Temporal Patterns of Holistic Functional Brain Networks via Multi-Head Guided Attention Graph Neural Networks (Multi-Head GAGNNs)[J]. Medical Image Analysis, 2022
Multi-head GAGNN: A Multi-head Guided Attention Graph Neural Network for Modeling Spatio-temporal Patterns of Holistic Brain Functional Networks[C]. MICCAI, 2021

e-mail address: jiadong.yan@mail.mcgill.ca

tensorflow 1.10 on GTX 1080 Ti

mh_gagnn_spatial.py
(1) inputs:
all inputs are defined in function load_data()
"train_path" is the path of the preprocessed brain data
"label_path" is the path of the labels

(2) outputs:
"result.txt" file to record the training loss and testing loss
and ten .mat files are the results of the modeled ten RSN spatial patterns 

mh_gagnn_temporal.py
(1) inputs:
all inputs are defined in function load_data()
"train_path" is the path of the preprocessed brain data
"label_path" is the path of the labels
"spatial_p" is the modeled spatial patterns via spatial network which is also the input of the temporal network

(2) outputs:
"result.txt" file to record the training loss and testing loss
and ten .mat files are the results of the modeled ten RSN temporal patterns 
