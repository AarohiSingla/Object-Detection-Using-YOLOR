# Object-Detection-Using-YOLOR
You Only Learn One Representation

Command to train your algorithm:  python train.py --batch-size 8 --img 1280 1280 --data custom.yaml --cfg cfg/yolor_p6_custom.cfg --weights '' --device 0 --name yolor_p6 --hyp hyp.scratch.1280.yaml --epochs 300 

For Detections:  python detect.py --source inference/images/e.jpg --cfg cfg/yolor_p6_custom.cfg --weights runs\train\exp6\weights\best.pt --conf 0.25 --img-size 1280 --device 0 --names data/custom.names



