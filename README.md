# FasterRCNN-TransferLearning-Tensorflow

Implementation of Faster RCNN training on Snapshot Serengeti model using Tensorflow v1. The reason for using v1 instead of v2 is due to requirement of "--additional_output_tensor_names detection_features" while exporting as we need the detection features while training the Context RCNN model.
