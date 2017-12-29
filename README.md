# Vehicle Detection 
```
## Compare different model using same dataset
```
1. [YoloV2](https://github.com/eric612/yolov2-windows)

2. [FasterRCNN](https://github.com/intel/caffe)

3. [SSD](https://github.com/eric612/MobileNet-SSD-windows)



### Customize YOLOv2 

1. Better performance on small vehicle detection , but will add false object more
2. light weight (30M , 27% size of full yolov2)
3. 1.5x faster of full yolov2 (CPU forward)
4. Only has conv,max pooling and region loss layer

#### Result

[![1](https://img.youtube.com/vi/9pS3Ov_b-Qg/0.jpg)](https://www.youtube.com/watch?v=9pS3Ov_b-Qg)

[![1](https://img.youtube.com/vi/EU51rO3M6yo/0.jpg)](https://www.youtube.com/watch?v=EU51rO3M6yo)

#### Training

weights download [here](https://drive.google.com/open?id=1Ul8yRlvzcr8nsn5yfm9G_pdxqHVYsryY)

train command
```
darknet detector train data/voc.data yolo-voc-custom.cfg car.conv.14
```

### Original YOLOv2 

#### Model download

weights download [here](https://drive.google.com/open?id=1pfGqD00STsauvBAnj6UyzNlgSJugm89q)

#### Result

[![1](https://img.youtube.com/vi/kuKnOTDIbq4/0.jpg)](https://www.youtube.com/watch?v=kuKnOTDIbq4)

[![2](https://img.youtube.com/vi/OlNxMPkwxyQ/0.jpg)](https://www.youtube.com/watch?v=OlNxMPkwxyQ)

[![3](https://img.youtube.com/vi/FEb4SWWBjLA/0.jpg)](https://www.youtube.com/watch?v=FEb4SWWBjLA)

[![4](https://img.youtube.com/vi/WThUZUfJMMQ/0.jpg)](https://www.youtube.com/watch?v=WThUZUfJMMQ)

[![5](https://img.youtube.com/vi/3KSccLecHEM/0.jpg)](https://www.youtube.com/watch?v=3KSccLecHEM)

### FasterRCNN Model

[VGG16](https://drive.google.com/open?id=1NQ9F74FTZnXM-hyuwYAoDBOYBjDSf5bp)

[VGG19](https://drive.google.com/open?id=1FiSktKooiABZJB5UIun9tAmD5aTEAHxn)

### FasterRCNN Result 

####VGG19

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/NhID_pNwgac/0.jpg)](https://www.youtube.com/watch?v=NhID_pNwgac)

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/AjnaTelt0KM/0.jpg)](https://www.youtube.com/watch?v=AjnaTelt0KM)

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/vxk77dicGAQ/0.jpg)](https://www.youtube.com/watch?v=vxk77dicGAQ)

####VGG16

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/xjIB9t1tLOg/0.jpg)](https://www.youtube.com/watch?v=xjIB9t1tLOg)

### SSD Model

Download weights and prototxt [here](https://drive.google.com/open?id=1RdRDzfhVtzX27Lp8clv5mahyTf0O-O8Y)

### SSD Result 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/xu9MkkufG0g/0.jpg)](https://www.youtube.com/watch?v=xu9MkkufG0g)

### Source Video

[street](https://drive.google.com/open?id=1Wkk_n_yXz0C8nuwPK_1B8bJVJf7vzWeB)

[tunnel](https://drive.google.com/open?id=1TDdBmZDtm_02WCLM3ENvnNnm6jUmeJFu)

[rear view](https://drive.google.com/open?id=1pJQ4F1jqUHywI9bw0r2f3R-xyJOghujm)

[night 1](https://drive.google.com/open?id=1r2QyxgAy_dt_30rWZXcHG5TE0zltXdkY)

[night 2](https://drive.google.com/open?id=11NKTl15IPMdowTZnVVW8_HAYSdpTeJU-)

