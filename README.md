The purpose of this repository is to study numerical optimization techniques and their application in the design of convolutional neural networks.

Currently implemented:
* assignment of the maximum amount of layer output channels such that a predefined maximum peak memory is not exceeded
  * [] WIP DeepLabV3 segmentation network (need to implement constraints on layers that do not change the number of output channels or require the same input channels at their inputs)

We make use of the tflite-tools repository for tensor lifeness and scheduling analysis.