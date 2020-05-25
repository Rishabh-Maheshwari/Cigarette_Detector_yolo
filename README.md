# Cigarette_Detector_yolo
Developing a cigarette detector model using YOLO algorithm from scracth.
# Deep learning based Cigarette detection using the YOLOv3 algorithm


## Getting started

The YOLOv3 (You Only Look Once) is a state-of-the-art, real-time object detection algorithm. The published model recognizes 80 different objects in images and videos. For more details, you can refer to this [paper](https://pjreddie.com/media/files/papers/YOLOv3.pdf).

## YOLOv3's architecture

![Imgur](https://github.com/sthanhng/yoloface/blob/master/assets/yolo-architecture.png)

## OpenCV Deep Neural Networks (dnn module)

OpenCV `dnn` module supports running inference on pre-trained deep learning models from popular frameworks such as TensorFlow, Torch, Darknet and Caffe.
## Usage

* Clone this repository
```bash
$ git clone https://github.com/sthanhng/yoloface
```
* Run the following command:

>**video input**
```bash
$ python yoloface.py --video samples/subway.mp4 --output-dir outputs/
```

>**webcam**
```bash
$ python yoloface.py --src 1 --output-dir outputs/
```

## Sample outputs

![Imgur](assets/outside_000001_yoloface.jpg)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for more details.
