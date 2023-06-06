### MMdet精度
        Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.784
        Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.969
        Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.950
        Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000
        Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = -1.000
        Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.784
        Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.814
        Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.814
        Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.814
        Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000
        Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = -1.000
        Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.814
        06/05 23:48:21 - mmengine - INFO - bbox_mAP_copypaste: 0.784 0.969 0.950 -1.000 -1.000 0.784
        06/05 23:48:22 - mmengine - INFO - Epoch(test) [11/11]    coco/bbox_mAP: 0.7840  coco/bbox_mAP_50: 0.9690  coco/bbox_mAP_75: 0.9500  coco/bbox_mAP_s: -1.0000  coco/bbox_mAP_m: -1.0000  coco/bbox_mAP_l: 0.7840  data_time: 0.8036  time: 1.1060

### MMpose精度
        Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets= 20 ] =  0.744
        Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets= 20 ] =  1.000
        Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets= 20 ] =  0.886
        Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets= 20 ] = -1.000
        Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets= 20 ] =  0.744
        Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 20 ] =  0.774
        Average Recall     (AR) @[ IoU=0.50      | area=   all | maxDets= 20 ] =  1.000
        Average Recall     (AR) @[ IoU=0.75      | area=   all | maxDets= 20 ] =  0.929
        Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets= 20 ] = -1.000
        Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets= 20 ] =  0.774
        06/06 23:25:53 - mmengine - INFO - Evaluating PCKAccuracy (normalized by ``"bbox_size"``)...
        06/06 23:25:53 - mmengine - INFO - Evaluating AUC...
        06/06 23:25:53 - mmengine - INFO - Evaluating NME...
        06/06 23:25:53 - mmengine - INFO - Epoch(test) [6/6]    coco/AP: 0.744119  coco/AP .5: 1.000000  coco/AP .75: 0.886209  coco/AP (M): -1.000000  coco/AP (L): 0.744119  coco/AR: 0.773810  coco/AR .5: 1.000000  coco/AR .75: 0.928571  coco/AR (M): -1.000000  coco/AR (L): 0.773810  PCK: 0.972789  AUC: 0.127268  NME: 0.040863  data_time: 1.297488  time: 2.803812


### 预测图片
![image](https://github.com/Ldixuan/OpenMMLab_homework1/blob/master/ear.jpg)

### 预测视频
![image](https://github.com/Ldixuan/OpenMMLab_homework1/blob/master/ear.gif)