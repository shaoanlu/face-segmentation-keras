# face_segmentation_keras
A port of [YuvalNirkin/face_segmentation](https://github.com/YuvalNirkin/face_segmentation) repo to keras.

## Descriptions

1. [FCN8s_caffe2keras_weights.ipynb](https://github.com/shaoanlu/face_segmentation_keras/blob/master/FCN8s_caffe2keras_weights.ipynb)
  - This notebook download FCN8s caffe model from YuvalNirkin's repo and convert it to a keras weights file.
2. [FCN8s_keras_demo.ipynb](https://github.com/shaoanlu/face_segmentation_keras/blob/master/FCN8s_keras_demo.ipynb)
  - This notebook is the demo of keras FCN8s for face segmentation.
3. Keras weights file
  - Converted keras weights file `Keras_FCN8s_face_seg_YuvalNirkin.h5` (through [FCN8s_caffe2keras_weights.ipynb](https://github.com/shaoanlu/face_segmentation_keras/blob/master/FCN8s_caffe2keras_weights.ipynb)) can be found [here](https://drive.google.com/open?id=1alyR6uv4CHt1WhykiQIiK5MZir7HSOUU).

## Results

**Update Jun. 5th, 2018:** The author contacted me, and [mentioned](https://github.com/shaoanlu/face-segmentation-keras/issues/3) that the the original model was trained on preprocessed (detecting and cropping) data. Applying the model on full images, such as the following examples, will yield poor results. Please visit the [official repo](https://github.com/YuvalNirkin/face_segmentation) for more detail.

### Successful cases

![1](https://www.dropbox.com/s/s8uzck810x4it0g/1.png?raw=1)

![2](https://www.dropbox.com/s/tjpwn3he7p40w4p/2.png?raw=1)

![3](https://www.dropbox.com/s/eub6et9s5p8rl07/3.png?raw=1)

### Failure cases

![4](https://www.dropbox.com/s/picdtqxkqkp76gz/4.png?raw=1)

![5](https://www.dropbox.com/s/9lufy3b5c0dnxei/5.png?raw=1)


###### Images are from [Pexels](https://www.pexels.com/), [GAHANG](http://gahag.net/), and [PAKUTASO](https://www.pakutaso.com/).
