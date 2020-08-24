# Pigeon-Detection
This repository contains Pigeon detection sourcecode on the jetson nano platform 

reference github code
https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10



.pb to .onnx converion : 



converting onnx to trt : 
onnx2trt model.onnx -b 1 -w 2 -o engine.trt

one line command to install pycuda : 
sudo pip3 install --global-option=build_ext --global-option="-I/usr/local/cuda/include" --global-option="-L/usr/local/cuda/lib64" pycuda


