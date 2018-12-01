# keras-yolo3


Keras-yolo3 on Kitti Data Object Tracking dataset 

1. Git clone this repository 
2. $ cd keras-yolo3
3. $ virtualenv -p python3 venv 
4. $ source venv/bin/activate 
5. $ pip install -r requirements.txt 
6. $ export PYTHONPATH="/home/hc/github/keras-yolo3" <- change path to your repo
7. $ source venv/bin/activate
8. $ python3 train.py -c config_kitti.json <- run training

Note: modifiy config_kitti.json to match your environment i.e. chagne the following labels, "train_image_folder", "train_annot_folder", and "saved_weights_name"



Reference and more details: https://github.com/experiencor/keras-yolo3

See the following repo for instruction to get the complete kitti object tracking dataset
https://github.com/Henrykanchen/vod-converter


