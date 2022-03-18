# Driver Identification Using Deep Learning
# usage
# Collect data on drivers.
- Train the driver identification/classification model using the provided architecture.
- Setup the personalised drivers profiles on AGL.
- Use the provided Flask server to communicate between Automotive Grade Linux and the driver identification model.

#Training the Driver Identification model

If you want to retrain the model using the FCN-LSTM architecture you can use the model in the training folder, it contains:

- The driver identification model using FCN-LSTM.
- The implemented anomalies detection using One-Class SVM.
- The tests of the performance of the model with some anomalies injected in the data.
- The used data in that example is the security dataset, it's available for download from this link: http://ocslab.hksecurity.net/Datasets/driving-dataset
