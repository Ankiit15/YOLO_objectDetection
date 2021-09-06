# YOLO_objectDetection

## If you are starting with YOLO, this is the first thing you need to do.

git clone https://github.com/pjreddie/darknet
cd darknet
make

## It should go all fine, and you have the darknet platform installed. The next step will be to download pre-trained weights. We will download the default weights and also the optimised weights and try them.

wget https://pjreddie.com/media/files/yolov3.weights

wget https://pjreddie.com/media/files/yolov3-tiny.weights

Download anyone of those two. yolo-tiny is a smaller, faster but slightly less accurate model.

## The files needed are:

yolov3.cfg – The standard config file used. This will be in the cfg/ directory. (In Darknet)

yolo-tiny.cfg – The speed optimised config file. This will be in the cfg/ directory. (In Darknet)

yolov3.weights – Pre-trained weights file for yolov3. This file is in the darknet/ directory. (Downloaded)

yolo-tiny.weights – Pre-trained speed optimised weight file. This file is in the darknet directory. (Downloaded)

coco.names – List of items, that the model can recognise is also in the data/ directory (In Darknet)

coco.data – A config data file kept in the cfg/ directory (In Darknet)


## Run image_YOLO.py for image files
## Run video_YOLO.py for videos



