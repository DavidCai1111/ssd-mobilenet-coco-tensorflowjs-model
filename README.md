# ssd-mobilenet-coco-tensorflowjs-model

[Tensorflow.js](https://js.tensorflow.org) pretrained model of [ssd_mobilenet_v1_0.75_depth_coco](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)

## How to use it?

### Clone this repository

```sh
git clone https://github.com/DavidCai1993/ssd-mobilenet-coco-tensorflowjs-model.git
```

### Load `model.json` in your tensorflow.js application

```js
'use strict'
const tf = require('@tensorflow/tfjs')
require('@tensorflow/tfjs-node')

;(async function () {
  const model = await tf.loadModel(`file://${__dirname}/ssd-mobilenet-coco-tensorflowjs-model/model/model.json`)

  // ...
})(console.error)

```
