# AICL

#### 1、Prepare environment

A100 + Python 3.10 + torch 2.3.1 + CUDA Version: 12.2

cd bin;

pip install -r requirements.txt



#### 2、Prepare data

Get data from [here](https://drive.google.com/drive/folders/1n_EpYf_K7tx0VWNVCFp4_yNKyN6AyScs);

cd bin;

python balance_training_data.py;



#### 3、Train

cd bin;

sh train.sh;



#### 4、Test

cd bin;

sh run_inference.sh;



#### 5、Eval

cd bin;

python evaluation.py test.jsonl predict.jsonl task_type task_name;





