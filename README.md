# image-captioning-style-transfer
Image captioning with vanilla RNNs and LSTMs on the [COCO dataset](http://cocodataset.org/#home). Network visualizations and style transfer on [SqueezeNet](https://github.com/DeepScale/SqueezeNet), which is a deep CNN pretrained to perform image classification on ImageNet.

* [Vanilla RNN Captioning](https://github.com/alexvlis/image-captioning-style-transfer/blob/master/RNN_Captioning.ipynb)
* [LSTM Captioning](https://github.com/alexvlis/image-captioning-style-transfer/blob/master/LSTM_Captioning.ipynb)
* [SqueezeNet Network Visualizations](https://github.com/alexvlis/image-captioning-style-transfer/blob/master/NetworkVisualization-TensorFlow.ipynb)
* [Style Transfer](https://github.com/alexvlis/image-captioning-style-transfer/blob/master/StyleTransfer-TensorFlow.ipynb)

## Installation ##
`sudo pip install virtualenv`<br />
`virtualenv -p python3 .env`<br />
`source .env/bin/activate`<br />
`pip install -r requirements.txt`<br />
`pip install -r requirements_tf.txt`<br />

## Download Data ##
`cd deeplearning/datasets/`<br />
`./get_data.sh`<br />
