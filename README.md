# deepfake_detection_papers

记录阅读过的deepfake detection相关论文:)

|年份|文章名称|代码仓库|阅读总结|想法|
|:--:|:--:|:--:|:--:|:--:|
|2019|[FaceForensics++: Learning to Detect Manipulated Facial Images](https://openaccess.thecvf.com/content_ICCV_2019/html/Rossler_FaceForensics_Learning_to_Detect_Manipulated_Facial_Images_ICCV_2019_paper.html)|[link](github.com/ondyari/FaceForensics)|将伪造检测视为被操纵视频的逐帧二元分类问题||
|2021|[Exploring Temporal Coherence for More General Video Face Forgery Detection](https://openaccess.thecvf.com/content/ICCV2021/html/Zheng_Exploring_Temporal_Coherence_for_More_General_Video_Face_Forgery_Detection_ICCV_2021_paper.html) | [link](https://github.com/yinglinzheng/FTCN) | 这篇文章提供了对帧与帧之间的伪造区域的可视化方法 |  |
|2023CVPR|[AltFreezing for More General Video Face Forgery Detection](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_AltFreezing_for_More_General_Video_Face_Forgery_Detection_CVPR_2023_paper.html)|[link](https://github.com/ZhendongWang6/AltFreezing)|针对以往在伪造检测中单独侧重时间/空间特征的问题，这篇文章提出了名为AltFreezing的训练策略(training strategy)，将三维卷积网络的模型参数分为空间相关和时间相关两部分，在训练过程中交替地冻结这两部分，使模型可以同时学习到时间特征和空间特征来区分真实视频和伪造视频。此外，还提出了视频级别的数据增强方法(video-level data augmentation methods)||
|2025NIPS|[SpeechForensics: Audio-Visual Speech Representation Learning for Face Forgery Detection](https://openreview.net/forum?id=ZsS0megTsh)|[link](https://github.com/Eleven4AI/SpeechForensics)|||
|2024arxiv|[DiMoDif: Discourse Modality-information Differentiation for Audio-visual Deepfake Detection and Localization](https://arxiv.org/abs/2411.10193)||||
