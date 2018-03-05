# image-captioning-style-transfer
Exploration of image captioning with vanilla RNNs and LSTMs on the COCO dataset, as well as network visualizations and style transfer on SqueezeNet.

* [Vanilla RNN Captioning](https://github.com/alexvlis/image-captioning-style-transfer/blob/master/RNN_Captioning.ipynb)
* [LSTM Captioning](https://github.com/alexvlis/image-captioning-style-transfer/blob/master/LSTM_Captioning.ipynb)
* [SqueezeNet Network Visualizations](https://github.com/alexvlis/image-captioning-style-transfer/blob/master/NetworkVisualization-TensorFlow.ipynb)
* [Style Transfer](https://github.com/alexvlis/image-captioning-style-transfer/blob/master/StyleTransfer-TensorFlow.ipynb)

##Installation##
`sudo pip install virtualenv`
`virtualenv -p python3 .env`
`source .env/bin/activate`
`pip install -r requirements.txt`
`pip install -r requirements_tf.txt`

##Download Data##
`cd deeplearning/datasets/`
`./get_data.sh`
