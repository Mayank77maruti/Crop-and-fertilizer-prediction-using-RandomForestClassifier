Dataset used - https://www.kaggle.com/datasets/mayankmohapatra77/crop-and-fertilizer-dataset/

Result:-


=== CROP MODEL ===
Model Accuracy: 99.70%
Classification Report:
              precision    recall  f1-score   support

       apple       1.00      1.00      1.00        17
      banana       1.00      1.00      1.00        17
   blackgram       1.00      1.00      1.00        16
    chickpea       1.00      1.00      1.00        25
     coconut       1.00      1.00      1.00        21
      coffee       1.00      1.00      1.00        13
      cotton       1.00      1.00      1.00         9
      grapes       1.00      1.00      1.00        10
        jute       0.94      1.00      0.97        15
 kidneybeans       1.00      1.00      1.00        16
      lentil       1.00      1.00      1.00         8
       maize       1.00      1.00      1.00        15
       mango       1.00      1.00      1.00        13
   mothbeans       1.00      1.00      1.00        15
    mungbean       1.00      1.00      1.00        13
   muskmelon       1.00      1.00      1.00        15
      orange       1.00      1.00      1.00        11
      papaya       1.00      1.00      1.00        19
  pigeonpeas       1.00      1.00      1.00        19
 pomegranate       1.00      1.00      1.00        17
        rice       1.00      0.92      0.96        13
  watermelon       1.00      1.00      1.00        13

    accuracy                           1.00       330
   macro avg       1.00      1.00      1.00       330
weighted avg       1.00      1.00      1.00       330


=== FERTILIZER MODEL ===
Model Accuracy: 100.00%
Classification Report:
              precision    recall  f1-score   support

    10-10-10       1.00      1.00      1.00       197
    17-17-17       1.00      1.00      1.00        32
         DAP       1.00      1.00      1.00        28
         MOP       1.00      1.00      1.00        34
        Urea       1.00      1.00      1.00        39

    accuracy                           1.00       330
   macro avg       1.00      1.00      1.00       330
weighted avg       1.00      1.00      1.00       330


=============================================
   CROP & FERTILIZER RECOMMENDATION SYSTEM
=============================================
Enter Nitrogen (N) value       : 60
Enter Phosphorus (P) value     : 50
Enter Potassium (K) value      : 20
Enter Temperature (°C)         : 24
Enter Humidity (%)             : 65
Enter pH level                 : 6.8
Enter Rainfall (mm)            : 90

Available soil types: ['Black', 'Clayey', 'Loamy', 'Sandy', 'Sandy Loam']
Enter Soil Type                : Loamy

=============================================
           PREDICTION RESULTS
=============================================
  🌾 Recommended Crop       : maize
  🧪 Recommended Fertilizer : 10-10-10
=============================================
