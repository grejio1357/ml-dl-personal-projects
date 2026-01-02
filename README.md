
## 📂 Project List

1. **ML Classification**  
   - Algorithms: Decision Tree, Random Forest, SVM, etc.  
   - Description: Predict datasets using various classification algorithms.  
   - File: `ml_classification.ipynb`  

2. **ML Regression**  
   - Algorithms: Linear Regression, Random Forest Regressor, etc.  
   - Description: Train and evaluate numerical prediction models.  
   - File: `ml_regression.ipynb`  

3. **CNN Image Classification (From Scratch)**  
   - Description: Implemented a CNN model from scratch using pytorch.  
   - File: `cnn_new_model.ipynb`  

4. **CNN Image Classification (Pretrained Model)**  
   - Description: Used pretrained models such as ResNet and VGG for image classification.  
   - File: `cnn_pretrained.ipynb`  

5. **LSTM for Time Series**  
   - Description: Solving time series prediction problems using LSTM networks.  
     This project handles irregular/uneven time series data, demonstrating preprocessing and modeling for non-uniform intervals.  
   - File: `lstm.ipynb`

   Model Performance / Scores

1. **ML Classification**: Accuracy 79% on test set(f1-score)
2. **ML Regression**: R² 0.97 
3. **CNN From Scratch**: Test accuracy 34%  
4. **CNN Pretrained**: 
     resnet_model:     
     Top-1 Accuracy: 0.8452, Top-5 Accuracy: 0.9582

     vgg_model:        
     Top-1 Accuracy: 0.8383, Top-5 Accuracy: 0.9554

     alexnet_model:    
     Top-1 Accuracy: 0.7095, Top-5 Accuracy: 0.8927
       
5. **LSTM Time Series**:
     Test MSE Loss = 0.00215
     Accuracy within 5% tolerance = 0.043
     Accuracy within 10% tolerance = 0.090