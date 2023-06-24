# Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data
This is a deep learning project on Stock Price prediction and model performance comparison using multivariate time series data which me and my partner Lakshmi Sravanthi Naupada have done together.
<img width="838" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/352fda4d-0c24-4948-b3d2-432195dcd90f">
<img width="1004" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/50aef120-76dd-49a0-9522-949bba2331b0">
Architecture of the models: Implemented LSTM with dropout layers and Transformers with multi-head attention and dropout layers in the architecture of the models respectively.
LSTM losses are as below:
<img width="623" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/e3099f60-2b02-4542-a8f7-fa9deab65878">
Transformer losses are as below:
<img width="937" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/2e3d7773-fa87-43d9-b1a7-0cd4afb4edcc">
KPIs of LSTM model is as below:
<img width="282" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/8b7124a2-32ae-4a24-b6be-48bd85083f50">
KPIs of Transformer model is as below:
<img width="427" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/fcea11bc-f72c-4ba4-a3ba-3ca0c63980bd">
We saw significant deviation of different KPIs of the Transformer model whereas the LSTM model showed good performance and hence it also predicted the future stock prices very well:
LSTM predictions:
<img width="239" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/79052b04-8d4d-45b2-bd28-c14c237bc094">
<img width="650" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/8951a1a2-bd11-4361-820a-27ce71198724">
Transformer predictions:
<img width="257" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/503c87a4-2eb6-4f06-b8a7-5af707ddcfa1">
<img width="667" alt="image" src="https://github.com/PretomGhosh/Stock-Price-prediction-and-model-performance-comparison-using-multivariate-time-series-data/assets/34418713/2d588c60-c3c4-4fe9-9006-f6cc3c3e12ac">
So we can say that the LSTM worked very well with the dataset compared to Transformer model
Libraries used:
Pandas, Numpy, Keras, TensoFlow, Sklearn, matplotlib, seaborn
Models used:
LSTM, TNN
Highlighted works done: 
EDA, 10 fold cross validation, Hyperparameter tuning, training, testing, prediction, performance measurement
