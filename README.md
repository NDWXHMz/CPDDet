## CPDDet: Collaborative Pseudo-labeling and Prototype Disentanglement Detector for Remote Sensing Open-World Object Detection

---

## Abstract

---

>Closed-set remote sensing detectors have achieved substantial progress, but their fixed label spaces limit reliable responses to foreground objects beyond predefined categories in evolving real-world scenes. Open world object detection (OWOD) provides a task framework for localizing such out-of-category foreground objects as ``Unknown''. However, current remote sensing OWOD benchmarks typically simulate open-world evaluation by splitting closed-set categories into known and unknown classes, in which unannotated valid foreground instances may be counted as background false positives, biasing unknown object detection evaluation. Existing OWOD methods also suffer from unstable unknown pseudo-labels, supervision conflicts between unknown and background classes, and entangled unknown features. To address these issues, this study constructs two remote sensing OWOD benchmarks, DOTA-UN and DIOR-UN, by supplementing annotations for potential unknown foreground instances through a visual foundation model-driven unknown object annotation pipeline. Based on these benchmarks, this study proposes a Collaborative Pseudo-labeling and Prototype Disentanglement Detector (CPDDet). Within CPDDet, the Collaborative Perception Pseudo-label Generator integrates complementary feature cues to stabilize unknown pseudo-label selection and filters ambiguous high-uncertainty samples to alleviate unknown-background supervision conflict. In addition, the Progressive Prototype Disentanglement Head extends the single-node unknown representation into a multi-prototype space to guide heterogeneous unknown feature separation and reduce feature entanglement. Experiments on DOTA-UN and DIOR-UN show that CPDDet achieves a favorable balance between potential unknown object detection and known-class detection accuracy.

## ![image-20260527205418514](C:\Users\12636\Desktop\旋转遥感目标检测\论文\修改正文\投稿\github\README.assets\image-20260527205418514.png)

## Main Result

---

### On DOTA-UN

#### DOTA-UN 11-4 setting

![image-20260527205544362](C:\Users\12636\Desktop\旋转遥感目标检测\论文\修改正文\投稿\github\README.assets\image-20260527205544362.png)

#### DOTA-UN 8-7 setting

![image-20260527205600540](C:\Users\12636\Desktop\旋转遥感目标检测\论文\修改正文\投稿\github\README.assets\image-20260527205600540.png)

### On DIOR-UN

![image-20260527214459262](C:\Users\12636\Desktop\旋转遥感目标检测\论文\修改正文\投稿\github\README.assets\image-20260527214459262.png)

## Visualization Result

### On DOTA-UN

![image-20260527214549328](C:\Users\12636\Desktop\旋转遥感目标检测\论文\修改正文\投稿\github\README.assets\image-20260527214549328.png)

### On DIOR-UN

![image-20260527214559826](C:\Users\12636\Desktop\旋转遥感目标检测\论文\修改正文\投稿\github\README.assets\image-20260527214559826.png)

## The code and data will be made publicly available upon the acceptance of the paper.