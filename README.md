# PotSpot
Potholes Detection System using smartphone's sensors.

This project includes 3 major phases.
1. Data Collection
2. Training and Testing the Data using different models
3. Android app to detect PotHole.


1. DATA COLLECTION

For Data collection , we build a android application which collects the accelermeter's data and GPS coordinates. The application saves the data in the device itself in csv format. After that we identified the pattern of graphs when any pothole comes. So we wrote two scripts to labelled the training data.

2. Training and Testing 

We trained the data using different machine learing classifiers and compared the accuracy of each model. The Support Vector Machine ( SVM )
showed the highest accuracy.

3. App to detect Pothole

We build the android app which will automatically beeps when any pothole detects and save its gps coordinates in device to forward it to
concerned authorities so that maintainence can be taken care on time.
