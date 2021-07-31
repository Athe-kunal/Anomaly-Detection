#Anomaly Detection using LSTM in baldwin pump generator

Baldwin Pump is a sequential data and it possibly it has anomalies. This repository tries to find anomalies by LSTM networks (because of sequential data). It first encodes the data to a latent dimension and then decodes to original format. The intuition is as the machine is working for a longer period of time, it will have less anomalies. Hence the encoder the decoder error would be higher for those data points. Hence we keep a threshold based on error to filter out anomalies 
