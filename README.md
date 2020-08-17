# image_segmentation_clone

CT lung segmentation
build AI Model : from CT image, extract lung region mask
![result_img0.png](https://github.com/yhhyunn/image_segmentation_clone/raw/master/result_img0.png)

## Reference

빵형의 개발도상국 참조

- Code : https://github.com/kairess/CT_lung_segmentation
- Youtube : https://www.youtube.com/watch?v=z8lK69BQ0VE
- Dataset : https://www.kaggle.com/kmader/finding-lungs-in-ct-data

## Model Keywords

    - Convolutional Encoder-Decoder
    - Downsampling(MaxPooling2D)
    - Upsampling(UpSampling2D)

## System

    - Windows 10
    - Ryzen9 3900X
    - RTX 2070 Super

## Dependancies

    - Python
    - numpy
    - Keras
    - matplotlib
    * refer to requirements.txt

## Etc.

- Image save시 padding 없애기 : https://frhyme.github.io/python-lib/img_savefig_%EA%B3%B5%EB%B0%B1%EC%A0%9C%EA%B1%B0/
