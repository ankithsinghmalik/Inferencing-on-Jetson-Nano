# Inferencing-on-Jetson-Nano
In this particular repo you will find the code and steps of how to inference and optimize your custom trained model on jetson Nano

# Download the files
 Run this file PNEUMONIA_DETECTION_USING_Mobilenet.ipynb as save the model and download it on to your machine
 
 #Step2 
 
 Transfer the saved model from your pc to Jetson Nano using scp or any other favourable method
 
 #Step3
 
 Run the file Inferencing_Using_Mobilenet_v2_model_on_jetson_nano.ipynb which optimize the Mobilenet_custom_model using the TF-TRT and converts it to a lower precision FP16
 as jetson nano supports only precision mode till FP16
 
 Use that optimized model for the further inferencing on Jetson Nano
 
 
