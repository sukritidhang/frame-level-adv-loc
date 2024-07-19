# frame-level-adv-loc

This code is only  for academic and research purposes.


### Model

<p>The proposed  model Advert Segmentation Network (AdSegNet) [1],  accurately localizes  advert in outdoor scenes with ALOS [2]  dataset. We adopt our proposed model as the backbone
and test on  advert-based video to ensure that the proposed model is not specific to the dataset initially used. </p>

>[1] Dhang, S., Zhang, M. & Dev, S. AdSegNet: a deep network to localize billboard in outdoor scenes. SIViP (2024). https://doi.org/10.1007/s11760-024-03388-7 \\
> [2] Dev, S., Hossari, M., Nicholson, M., McCabe, K., Nautiyal, A., Conran,
C., Tang, J., Xu, W., Pitie, F.: The ALOS dataset for advert localization
in outdoor scenes. In: Proc. Eleventh International Conference on Quality
of Multimedia Experience (QoMEX) (2019)


### Scripts 

- predict_video_dataset_linknet_unet_adsegnet.ipynb : Run  this script to evaluate the model on video dataset. Generate frame-level predictions.
- eval_metric_iou.ipynb : Run this script to calculate evaluation metrics.