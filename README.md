# AnomalyDetection
Multivariant data analysis methods, namely PCA and LSTM Autoencoder, are applied to detect anomalies in the operating condition of control valves that are installed in a production plant. Built-in sensors record process parameters, such as stroke or signal pressure, which serve as a database. In the training process, a machine learning model is constructed and fed with normal historical data to learn an efficient representation of the healthy operating condition of the control valve. In the online anomaly detection phase, the goal is to detect the continuous degradation of the machine component. Therefore, data collected in the past week of the production process are processed by the loaded model to evaluate the current operating condition. The actual state is compared with the target state. The measured deviation represents the anomaly score. If the values are above a threshold defined in the training process, an anomaly is detected in the data. The analysis results are then integrated into a report for the plant operator. With this collected information, effective maintenance of the control valves can be planned and executed to reduce unnecessary repairs and unplanned machine downtime.

As the project was conducted with a partner company, data specific information cannot be shown due to privacy concerns. 

![](/Test11.PNG)
