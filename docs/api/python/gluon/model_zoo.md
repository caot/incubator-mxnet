# Gluon Model Zoo

```eval_rst
    .. currentmodule:: mxnet.gluon.model_zoo
```

## Overview

This document lists the model APIs in Gluon:

```eval_rst
.. autosummary::
    :nosignatures:

    mxnet.gluon.model_zoo
    mxnet.gluon.model_zoo.vision
```

The `Gluon Model Zoo` API, defined in the `gluon.model_zoo` package, provides pre-defined
and pre-trained models to help bootstrap machine learning applications.

In the rest of this document, we list routines provided by the `gluon.model_zoo` package.

### Vision

```eval_rst
.. currentmodule:: mxnet.gluon.model_zoo.vision
.. automodule:: mxnet.gluon.model_zoo.vision
```

The following table summarizes the available models.

| Alias         | Network                                                                               | # Parameters | Top-1 Accuracy | Top-5 Accuracy | Origin                                                                                                                                               |
|---------------|---------------------------------------------------------------------------------------|--------------|----------------|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| alexnet       | [AlexNet](https://arxiv.org/abs/1404.5997)                                            | 61,100,840   | 0.5492         | 0.7803         | Converted from pytorch vision                                                                                                                        |
| densenet121   | [DenseNet-121](https://arxiv.org/pdf/1608.06993.pdf)                                  | 8,062,504    | 0.7497         | 0.9225         | Converted from pytorch vision                                                                                                                        |
| densenet161   | [DenseNet-161](https://arxiv.org/pdf/1608.06993.pdf)                                  | 28,900,936   | 0.7770         | 0.9380         | Converted from pytorch vision                                                                                                                        |
| densenet169   | [DenseNet-169](https://arxiv.org/pdf/1608.06993.pdf)                                  | 14,307,880   | 0.7617         | 0.9317         | Converted from pytorch vision                                                                                                                        |
| densenet201   | [DenseNet-201](https://arxiv.org/pdf/1608.06993.pdf)                                  | 20,242,984   | 0.7732         | 0.9362         | Converted from pytorch vision                                                                                                                        |
| inceptionv3   | [Inception V3 299x299](http://arxiv.org/abs/1512.00567)                               | 23,869,000   | 0.7755         | 0.9364         | Converted from pytorch vision                                                                                                                        |
| mobilenet0.25 | [MobileNet 0.25](https://arxiv.org/abs/1704.04861)                                    | 475,544      | 0.5185         | 0.7608         | Trained with [script](https://github.com/apache/incubator-mxnet/blob/master/example/gluon/image_classification.py)              |
| mobilenet0.5  | [MobileNet 0.5](https://arxiv.org/abs/1704.04861)                                     | 1,342,536    | 0.6307         | 0.8475         | Trained with [script](https://github.com/apache/incubator-mxnet/blob/master/example/gluon/image_classification.py)              |
| mobilenet0.75 | [MobileNet 0.75](https://arxiv.org/abs/1704.04861)                                    | 2,601,976    | 0.6738         | 0.8782         | Trained with [script](https://github.com/apache/incubator-mxnet/blob/master/example/gluon/image_classification.py)              |
| mobilenet1.0  | [MobileNet 1.0](https://arxiv.org/abs/1704.04861)                                     | 4,253,864    | 0.7105         | 0.9006         | Trained with [script](https://github.com/apache/incubator-mxnet/blob/master/example/gluon/image_classification.py)              |
| mobilenetv2_1.0  | [MobileNetV2 1.0](https://arxiv.org/abs/1801.04381)                                | 3,539,136    | 0.7192         | 0.9056         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| mobilenetv2_0.75 | [MobileNetV2 0.75](https://arxiv.org/abs/1801.04381)                               | 2,653,864    | 0.6961         | 0.8895         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| mobilenetv2_0.5  | [MobileNetV2 0.5](https://arxiv.org/abs/1801.04381)                                | 1,983,104    | 0.6449         | 0.8547         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| mobilenetv2_0.25 | [MobileNetV2 0.25](https://arxiv.org/abs/1801.04381)                               | 1,526,856    | 0.5074         | 0.7456         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet18_v1   | [ResNet-18 V1](http://arxiv.org/abs/1512.03385)                                       | 11,699,112   | 0.7093         | 0.8992         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet34_v1   | [ResNet-34 V1](http://arxiv.org/abs/1512.03385)                                       | 21,814,696   | 0.7437         | 0.9187         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet50_v1   | [ResNet-50 V1](http://arxiv.org/abs/1512.03385)                                       | 25,629,032   | 0.7647         | 0.9313         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet101_v1  | [ResNet-101 V1](http://arxiv.org/abs/1512.03385)                                      | 44,695,144   | 0.7834         | 0.9401         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet152_v1  | [ResNet-152 V1](http://arxiv.org/abs/1512.03385)                                      | 60,404,072   | 0.7900         | 0.9438         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet18_v2   | [ResNet-18 V2](https://arxiv.org/abs/1603.05027)                                      | 11,695,796   | 0.7100         | 0.8992         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet34_v2   | [ResNet-34 V2](https://arxiv.org/abs/1603.05027)                                      | 21,811,380   | 0.7440         | 0.9208         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet50_v2   | [ResNet-50 V2](https://arxiv.org/abs/1603.05027)                                      | 25,595,060   | 0.7711         | 0.9343         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet101_v2  | [ResNet-101 V2](https://arxiv.org/abs/1603.05027)                                     | 44,639,412   | 0.7853         | 0.9417         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| resnet152_v2  | [ResNet-152 V2](https://arxiv.org/abs/1603.05027)                                     | 60,329,140   | 0.7921         | 0.9431         | Trained with [script](https://gluon-cv.mxnet.io/model_zoo/index.html#image-classification)                                      |
| squeezenet1.0 | [SqueezeNet 1.0](https://arxiv.org/abs/1602.07360)                                    | 1,248,424    | 0.5611         | 0.7909         | Converted from pytorch vision                                                                                                                        |
| squeezenet1.1 | [SqueezeNet 1.1](https://github.com/DeepScale/SqueezeNet/tree/master/SqueezeNet_v1.1) | 1,235,496    | 0.5496         | 0.7817         | Converted from pytorch vision                                                                                                                        |
| vgg11         | [VGG-11](https://arxiv.org/abs/1409.1556)                                             | 132,863,336  | 0.6662         | 0.8734         | Converted from pytorch vision                                                                                                                        |
| vgg13         | [VGG-13](https://arxiv.org/abs/1409.1556)                                             | 133,047,848  | 0.6774         | 0.8811         | Converted from pytorch vision                                                                                                                        |
| vgg16         | [VGG-16](https://arxiv.org/abs/1409.1556)                                             | 138,357,544  | 0.6986         | 0.8945         | Converted from pytorch vision                                                                                                                        |
| vgg19         | [VGG-19](https://arxiv.org/abs/1409.1556)                                             | 143,667,240  | 0.7072         | 0.8988         | Converted from pytorch vision                                                                                                                        |
| vgg11_bn      | [VGG-11 with batch normalization](https://arxiv.org/abs/1409.1556)                    | 132,874,344  | 0.6859         | 0.8872         | Converted from pytorch vision                                                                                                                        |
| vgg13_bn      | [VGG-13 with batch normalization](https://arxiv.org/abs/1409.1556)                    | 133,059,624  | 0.6884         | 0.8882         | Converted from pytorch vision                                                                                                                        |
| vgg16_bn      | [VGG-16 with batch normalization](https://arxiv.org/abs/1409.1556)                    | 138,374,440  | 0.7142         | 0.9043         | Converted from pytorch vision                                                                                                                        |
| vgg19_bn      | [VGG-19 with batch normalization](https://arxiv.org/abs/1409.1556)                    | 143,689,256  | 0.7241         | 0.9093         | Converted from pytorch vision                                                                                                                        |

```eval_rst
.. autosummary::
    :nosignatures:

    get_model
```

#### ResNet

```eval_rst
.. autosummary::
    :nosignatures:

    resnet18_v1
    resnet34_v1
    resnet50_v1
    resnet101_v1
    resnet152_v1
    resnet18_v2
    resnet34_v2
    resnet50_v2
    resnet101_v2
    resnet152_v2
```

```eval_rst
.. autosummary::
    :nosignatures:

    ResNetV1
    ResNetV2
    BasicBlockV1
    BasicBlockV2
    BottleneckV1
    BottleneckV2
    get_resnet
```

#### VGG

```eval_rst
.. autosummary::
    :nosignatures:

    vgg11
    vgg13
    vgg16
    vgg19
    vgg11_bn
    vgg13_bn
    vgg16_bn
    vgg19_bn
```

```eval_rst
.. autosummary::
    :nosignatures:

    VGG
    get_vgg
```

#### Alexnet

```eval_rst
.. autosummary::
    :nosignatures:

    alexnet
```

```eval_rst
.. autosummary::
    :nosignatures:

    AlexNet
```

#### DenseNet

```eval_rst
.. autosummary::
    :nosignatures:

    densenet121
    densenet161
    densenet169
    densenet201
```

```eval_rst
.. autosummary::
    :nosignatures:

    DenseNet
```

#### SqueezeNet

```eval_rst
.. autosummary::
    :nosignatures:

    squeezenet1_0
    squeezenet1_1
```

```eval_rst
.. autosummary::
    :nosignatures:

    SqueezeNet
```

#### Inception

```eval_rst
.. autosummary::
    :nosignatures:

    inception_v3
```

```eval_rst
.. autosummary::
    :nosignatures:

    Inception3
```

#### MobileNet

```eval_rst
.. autosummary::
    :nosignatures:

    mobilenet1_0
    mobilenet0_75
    mobilenet0_5
    mobilenet0_25
    mobilenet_v2_1_0
    mobilenet_v2_0_75
    mobilenet_v2_0_5
    mobilenet_v2_0_25
```

```eval_rst
.. autosummary::
    :nosignatures:

    MobileNet
    MobileNetV2
```

## API Reference

<script type="text/javascript" src='../../../_static/js/auto_module_index.js'></script>

```eval_rst

.. automodule:: mxnet.gluon.model_zoo

.. automodule:: mxnet.gluon.model_zoo.vision
    :members:
    :imported-members:

```

<script>auto_index("api-reference");</script>
