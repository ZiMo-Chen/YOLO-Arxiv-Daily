# 每日从arXiv中获取最新YOLO相关论文


## On the Potential of Open\-Vocabulary Models for Object Detection in Unusual Street Scenes

**发布日期**：2024-08-20

**作者**：Sadia Ilyas

**摘要**：Out\-of\-distribution \(OOD\) object detection is a critical task focused on
detecting objects that originate from a data distribution different from that
of the training data. In this study, we investigate to what extent
state\-of\-the\-art open\-vocabulary object detectors can detect unusual objects in
street scenes, which are considered as OOD or rare scenarios with respect to
common street scene datasets. Specifically, we evaluate their performance on
the OoDIS Benchmark, which extends RoadAnomaly21 and RoadObstacle21 from
SegmentMeIfYouCan, as well as LostAndFound, which was recently extended to
object level annotations. The objective of our study is to uncover
short\-comings of contemporary object detectors in challenging real\-world, and
particularly in open\-world scenarios. Our experiments reveal that open
vocabulary models are promising for OOD object detection scenarios, however far
from perfect. Substantial improvements are required before they can be reliably
deployed in real\-world applications. We benchmark four state\-of\-the\-art
open\-vocabulary object detection models on three different datasets.
Noteworthily, Grounding DINO achieves the best results on RoadObstacle21 and
LostAndFound in our study with an AP of 48.3% and 25.4% respectively.
YOLO\-World excels on RoadAnomaly21 with an AP of 21.2%.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.11221v1)

---


## Evaluating Image\-Based Face and Eye Tracking with Event Cameras

**发布日期**：2024-08-19

**作者**：Khadija Iddrisu

**摘要**：Event Cameras, also known as Neuromorphic sensors, capture changes in local
light intensity at the pixel level, producing asynchronously generated data
termed \`\`events''. This distinct data format mitigates common issues observed
in conventional cameras, like under\-sampling when capturing fast\-moving
objects, thereby preserving critical information that might otherwise be lost.
However, leveraging this data often necessitates the development of
specialized, handcrafted event representations that can integrate seamlessly
with conventional Convolutional Neural Networks \(CNNs\), considering the unique
attributes of event data. In this study, We evaluate event\-based Face and Eye
tracking. The core objective of our study is to showcase the viability of
integrating conventional algorithms with event\-based data, transformed into a
frame format while preserving the unique benefits of event cameras. To validate
our approach, we constructed a frame\-based event dataset by simulating events
between RGB frames derived from the publicly accessible Helen Dataset. We
assess its utility for face and eye detection tasks through the application of
GR\-YOLO \-\- a pioneering technique derived from YOLOv3. This evaluation includes
a comparative analysis with results derived from training the dataset with
YOLOv8. Subsequently, the trained models were tested on real event streams from
various iterations of Prophesee's event cameras and further evaluated on the
Faces in Event Stream \(FES\) benchmark dataset. The models trained on our
dataset shows a good prediction performance across all the datasets obtained
for validation with the best results of a mean Average precision score of 0.91.
Additionally, The models trained demonstrated robust performance on real event
camera data under varying light conditions.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.10395v1)

---


## YOLOv1 to YOLOv10: The fastest and most accurate real\-time object detection systems

**发布日期**：2024-08-18

**作者**：Chien\-Yao Wang

**摘要**：This is a comprehensive review of the YOLO series of systems. Different from
previous literature surveys, this review article re\-examines the
characteristics of the YOLO series from the latest technical point of view. At
the same time, we also analyzed how the YOLO series continued to influence and
promote real\-time computer vision\-related research and led to the subsequent
development of computer vision and language models.We take a closer look at how
the methods proposed by the YOLO series in the past ten years have affected the
development of subsequent technologies and show the applications of YOLO in
various fields. We hope this article can play a good guiding role in subsequent
real\-time computer vision development.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.09332v1)

---


## Infra\-YOLO: Efficient Neural Network Structure with Model Compression for Real\-Time Infrared Small Object Detection

**发布日期**：2024-08-14

**作者**：Zhonglin Chen

**摘要**：Although convolutional neural networks have made outstanding achievements in
visible light target detection, there are still many challenges in infrared
small object detection because of the low signal\-to\-noise ratio, incomplete
object structure, and a lack of reliable infrared small object dataset. To
resolve limitations of the infrared small object dataset, a new dataset named
InfraTiny was constructed, and more than 85% bounding box is less than 32x32
pixels \(3218 images and a total of 20,893 bounding boxes\). A multi\-scale
attention mechanism module \(MSAM\) and a Feature Fusion Augmentation Pyramid
Module \(FFAFPM\) were proposed and deployed onto embedded devices. The MSAM
enables the network to obtain scale perception information by acquiring
different receptive fields, while the background noise information is
suppressed to enhance feature extraction ability. The proposed FFAFPM can
enrich semantic information, and enhance the fusion of shallow feature and deep
feature, thus false positive results have been significantly reduced. By
integrating the proposed methods into the YOLO model, which is named
Infra\-YOLO, infrared small object detection performance has been improved.
Compared to yolov3, mAP@0.5 has been improved by 2.7%; and compared to yolov4,
that by 2.5% on the InfraTiny dataset. The proposed Infra\-YOLO was also
transferred onto the embedded device in the unmanned aerial vehicle \(UAV\) for
real application scenarios, where the channel pruning method is adopted to
reduce FLOPs and to achieve a tradeoff between speed and accuracy. Even if the
parameters of Infra\-YOLO are reduced by 88% with the pruning method, a gain of
0.7% is still achieved on mAP@0.5 compared to yolov3, and a gain of 0.5%
compared to yolov4. Experimental results show that the proposed MSAM and FFAFPM
method can improve infrared small object detection performance compared with
the previous benchmark method.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.07455v1)

---


## Vision Language Model for Interpretable and Fine\-grained Detection of Safety Compliance in Diverse Workplaces

**发布日期**：2024-08-13

**作者**：Zhiling Chen

**摘要**：Workplace accidents due to personal protective equipment \(PPE\) non\-compliance
raise serious safety concerns and lead to legal liabilities, financial
penalties, and reputational damage. While object detection models have shown
the capability to address this issue by identifying safety items, most existing
models, such as YOLO, Faster R\-CNN, and SSD, are limited in verifying the
fine\-grained attributes of PPE across diverse workplace scenarios. Vision
language models \(VLMs\) are gaining traction for detection tasks by leveraging
the synergy between visual and textual information, offering a promising
solution to traditional object detection limitations in PPE recognition.
Nonetheless, VLMs face challenges in consistently verifying PPE attributes due
to the complexity and variability of workplace environments, requiring them to
interpret context\-specific language and visual cues simultaneously. We
introduce Clip2Safety, an interpretable detection framework for diverse
workplace safety compliance, which comprises four main modules: scene
recognition, the visual prompt, safety items detection, and fine\-grained
verification. The scene recognition identifies the current scenario to
determine the necessary safety gear. The visual prompt formulates the specific
visual prompts needed for the detection process. The safety items detection
identifies whether the required safety gear is being worn according to the
specified scenario. Lastly, the fine\-grained verification assesses whether the
worn safety equipment meets the fine\-grained attribute requirements. We conduct
real\-world case studies across six different scenarios. The results show that
Clip2Safety not only demonstrates an accuracy improvement over state\-of\-the\-art
question\-answering based VLMs but also achieves inference times two hundred
times faster.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.07146v1)

---


## A lightweight YOLOv5\-FFM model for occlusion pedestrian detection

**发布日期**：2024-08-13

**作者**：Xiangjie Luo

**摘要**：The development of autonomous driving technology must be inseparable from
pedestrian detection. Because of the fast speed of the vehicle, the accuracy
and real\-time performance of the pedestrian detection algorithm are very
important. YOLO, as an efficient and simple one\-stage target detection method,
is often used for pedestrian detection in various environments. However, this
series of detectors face some challenges, such as excessive computation and
undesirable detection rate when facing occluded pedestrians. In this paper, we
propose an improved lightweight YOLOv5 model to deal with these problems. This
model can achieve better pedestrian detection accuracy with fewer
floating\-point operations \(FLOPs\), especially for occluded targets. In order to
achieve the above goals, we made improvements based on the YOLOv5 model
framework and introduced Ghost module and SE block. Furthermore, we designed a
local feature fusion module \(FFM\) to deal with occlusion in pedestrian
detection. To verify the validity of our method, two datasets, Citypersons and
CUHK Occlusion, were selected for the experiment. The experimental results show
that, compared with the original yolov5s model, the average precision \(AP\) of
our method is significantly improved, while the number of parameters is reduced
by 27.9% and FLOPs are reduced by 19.0%.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.06633v1)

---


## Optimal Preprocessing for Joint Detection and Classification of Wireless Communication Signals in Congested Spectrum Using Computer Vision Methods

**发布日期**：2024-08-13

**作者**：Xiwen Kang

**摘要**：The joint detection and classification of RF signals has been a critical
problem in the field of wideband RF spectrum sensing. Recent advancements in
deep learning models have revolutionized this field, remarkably through the
application of state\-of\-the\-art computer vision algorithms such as YOLO \(You
Only Look Once\) and DETR \(Detection Transformer\) to the spectrogram images.
This paper focuses on optimizing the preprocessing stage to enhance the
performance of these computer vision models. Specifically, we investigated the
generation of training spectrograms via the classical Short\-Time Fourier
Transform \(STFT\) approach, examining four classical STFT parameters: FFT size,
window type, window length, and overlapping ratio. Our study aims to maximize
the mean average precision \(mAP\) scores of YOLOv10 models in detecting and
classifying various digital modulation signals within a congested spectrum
environment. Firstly, our results reveal that additional zero padding in FFT
does not enhance detection and classification accuracy and introduces
unnecessary computational cost. Secondly, our results indicated that there
exists an optimal window size that balances the trade\-offs between and the time
and frequency resolution, with performance losses of approximately 10% and 30%
if the window size is four or eight times off from the optimal. Thirdly,
regarding the choice of window functions, the Hamming window yields optimal
performance, with non\-optimal windows resulting in up to a 10% accuracy loss.
Finally, we found a 10% accuracy score performance gap between using 10% and
90% overlap. These findings highlight the potential for significant performance
improvements through optimized spectrogram parameters when applying computer
vision models to the problem of wideband RF spectrum sensing.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.06545v1)

---


## Target Detection of Safety Protective Gear Using the Improved YOLOv5

**发布日期**：2024-08-12

**作者**：Hao Liu

**摘要**：In high\-risk railway construction, personal protective equipment monitoring
is critical but challenging due to small and frequently obstructed targets. We
propose YOLO\-EA, an innovative model that enhances safety measure detection by
integrating ECA into its backbone's convolutional layers, improving discernment
of minuscule objects like hardhats. YOLO\-EA further refines target recognition
under occlusion by replacing GIoU with EIoU loss. YOLO\-EA's effectiveness was
empirically substantiated using a dataset derived from real\-world railway
construction site surveillance footage. It outperforms YOLOv5, achieving 98.9%
precision and 94.7% recall, up 2.5% and 0.5% respectively, while maintaining
real\-time performance at 70.774 fps. This highly efficient and precise YOLO\-EA
holds great promise for practical application in intricate construction
scenarios, enforcing stringent safety compliance during complex railway
construction projects.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.05964v1)

---


## Advancing Pavement Distress Detection in Developing Countries: A Novel Deep Learning Approach with Locally\-Collected Datasets

**发布日期**：2024-08-10

**作者**：Blessing Agyei Kyem

**摘要**：Road infrastructure maintenance in developing countries faces unique
challenges due to resource constraints and diverse environmental factors. This
study addresses the critical need for efficient, accurate, and locally\-relevant
pavement distress detection methods in these regions. We present a novel deep
learning approach combining YOLO \(You Only Look Once\) object detection models
with a Convolutional Block Attention Module \(CBAM\) to simultaneously detect and
classify multiple pavement distress types. The model demonstrates robust
performance in detecting and classifying potholes, longitudinal cracks,
alligator cracks, and raveling, with confidence scores ranging from 0.46 to
0.93. While some misclassifications occur in complex scenarios, these provide
insights into unique challenges of pavement assessment in developing countries.
Additionally, we developed a web\-based application for real\-time distress
detection from images and videos. This research advances automated pavement
distress detection and provides a tailored solution for developing countries,
potentially improving road safety, optimizing maintenance strategies, and
contributing to sustainable transportation infrastructure development.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.05649v1)

---


## Livestock Fish Larvae Counting using DETR and YOLO based Deep Networks

**发布日期**：2024-08-09

**作者**：Daniel Ortega de Carvalho

**摘要**：Counting fish larvae is an important, yet demanding and time consuming, task
in aquaculture. In order to address this problem, in this work, we evaluate
four neural network architectures, including convolutional neural networks and
transformers, in different sizes, in the task of fish larvae counting. For the
evaluation, we present a new annotated image dataset with less data collection
requirements than preceding works, with images of spotted sorubim and dourado
larvae. By using image tiling techniques, we achieve a MAPE of 4.46% \($\\pm
4.70$\) with an extra large real time detection transformer, and 4.71% \($\\pm
4.98$\) with a medium\-sized YOLOv8.


**代码链接**：摘要中未找到代码链接。

**论文链接**：[阅读更多](http://arxiv.org/abs/2408.05032v1)

---

