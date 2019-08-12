To set up the dev enviornment:
run pip3 install -r requirements.txt
Currently running this in a docker container. Would probably work a bit better in an actual VM
as you would have access to cv2 windows and realtime video output. Currently testing by
running the scan and writing an image to the host machine under the /root directory.

Run download_dataset.sh to get the pre-built mask_rcnn_coco.h5 dataset

read https://github.com/matterport/Mask_RCNN if you want to train your own dataset and
obtain better results!

run $ python3 armory_overwatch.py
To grab the latest image from armorycam.com and run a scan on it.
