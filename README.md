
# People counter from video source
## Prerequests
- Install required packages
```
pip install -r requirements
```

## Running
```
python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt \
	--model mobilenet_ssd/MobileNetSSD_deploy.caffemodel \
	--input videos/example_01.mp4 --output output/output_01.avi
```


## Coming soon
Real time counting from camera source