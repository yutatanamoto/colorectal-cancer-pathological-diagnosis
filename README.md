# Colorectal cancer pathological diagnosis using machine learning    
## Usage  
```
$ sudo docker run -it -v $PWD:/pathology-finetune --gpus all --name pathology-finetune -p 8888:8888 tensorflow/tensorflow:latest-gpu-py3  
$ cd pathology-finetune
$ pip install -r requirements.txt
$ jupyter notebook --port 8888 --ip=0.0.0.0 --allow-root
```
