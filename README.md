# Pose-estimation-project

The main goal of Human pose estimation problem is to extract the position of body parts of every person appearing in an image or a video and use these key-points to build the skeleton representing the person's silhouette. This task does not use any sensors or detection systems but only deep learning networks more precisely convolutional pose machines.

A convolutional pose machine is a sequential architecture that composed of convolutional networks which directly operate on belief maps from previous stages, producing increasingly refined estimates for part locations. The expected output of this deep network is the set of skeletons superimposed on the media input(image, video, gif..), in order to train this network (supervised learning) we use labelled image datasets such as COCO dataset , extended-LSP, FLIC dataset ...
