# faster_rcnn_store

This is a python script to convert Faster RCNN body detection output to MOT17 challenge formation:

frame, id, bb-left, bb-top, bb-width, bb-height, conf, x, y, z 
id = -1 for person
x, y, z are for MOT3D, always -1 for 2D

https://motchallenge.net/data/MOT17/
