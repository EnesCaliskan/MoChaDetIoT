Modelling and change detection on IoT streaming data (MoChaDetIoT)

Team Members : <br/>

Uspenskaia Ekaterina <br/>
Caliskan Enes <br/>
Gyursoy Alexander-Efe <br/>
Nyikó Máté Szabolcs <br/>
József Szendrei <br/>

MoChaDetIoT project utilizes IoTID20 dataset which introduced in the paper "A Scheme for Generating a Dataset for Anomalous Activity Detection in IoT Networks" by Ullah et al. 
The dataset was generated in a controlled smart home environment using devices like the smart phone, AI speaker and security camera, connected via a Wi-Fi router. Malicious activities were simulated using attacking devices, while normal traffic was generated by legitimate IoT operations.

System Architecture : 
![alt text](https://github.com/Csorky/IoTNetworkNew/blob/main/arc.drawio.png)

Batch Processing Pipelines: <br/>
* Supervised Model : Decision Trees
* Unsupervised Model : KMeans, DBScan

Real-Time Stream Processing Pipelines: <br/>
* Exponential Moving Average (EMA)
* Sliding Window
* KDQ-Tree Detection (KDQ)
* Cumulative Sum (CUSUM)
* Drift Detection Method (DDM)
* ADaptive WINdowing (ADWIN)
* Page-Hinkley (PH)
* Linear Four Rates (LFR)
* Protocol Anomaly and Flow Metrics
* Margin Density Drift Detection Method (MD3)
* PCA-Based Change Detection (PCA-CD)
* Regression
* General Statistics
