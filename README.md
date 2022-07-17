# Image-Segmentation-with-Fully-Convolutional-Neural-Networks

we built a Fully Convolutional Neural Network for semantic image segmentation. we trained the model on a
custom dataset prepared by divamgupta. This contains video frames from a moving vehicle and is a
subsample of the CamVid dataset. we have made a VGG-16 network for the feature extraction , then
followed by an FCN-8 network for upsampling and generating the predictions. The output is segmentation
mask with predictions for 12 classes
