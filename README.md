# NYC Yellow Taxi Deep Learning SparkStreaming
Built a deep learning model on top of the NYC Yellow Taxi dataset using Keras. The dataset comprises of 65,092,557 records amounting to 5.8866 GBs. The dataset includes trips taken in all 5 boroughs in NYC for the year 2019 to 2021.

Used total_time (in seconds), total_distance (in miles), and month to predict fare prices in a year. 

<b>Hyperparameter testing</b>

Loss metric - Mean Squared Error, Mean Absolute Error <br>
Number of hidden layers - 1, 2, 3 layers <br>
Number of nodes in input layer - 16, 32 nodes <br>
Number of nodes in hidden layers - 32, 64 nodes <br>
Used chunks of data (~ 10000 rows) to evaluate hyperparameters for each model <br>

<img src="https://user-images.githubusercontent.com/38600655/206599126-7924cc4f-7ce2-4af6-8742-334be1789264.png" alt="drawing" width="400"/>
<img src="https://user-images.githubusercontent.com/38600655/206598994-cf174a95-9560-49e1-8db9-37e37661b163.png" alt="drawing" width="400"/>


<b>Final model</b>


<img src="https://user-images.githubusercontent.com/38600655/206599581-96a462ad-848f-4e9b-b597-36631abf5be7.png" alt="drawing" width="400"/>



