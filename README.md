# SSD-image-segmentation
Implementation of a resnet image segmentation library

* Bounding box based image segmentation
* feature pyramid network (4 layer CNN) with a network to classify bounding boxes and a second subnet to regress bounding box coordinates
* Focal loss used for dense object detection to offset both class imbalances and focus training on hard negative examples (based on FAIR research paper for dense object detection)
