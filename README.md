## 【AAAI 2026】GenVidBench: A 6-Million Benchmark for AI-Generated Video Detection
Zhen-Liang Ni*, Qiangyu Yan*, Mouxiao Huang, Tianning Yuan, Yehui Tang
Hailin Hu✉️, Xinghao Chen✉️, Yunhe Wang✉️

Dataset Download: 
[HuggingFace](https://huggingface.co/datasets/jian-0/GenVidBench) ; [BaiDuYun](https://pan.baidu.com/s/1KWg3znu14AOC6iOOT_iqMg#list/path=%2F) (The code is : 6Bb4)

News
---
2025/11/09: Good news! Our paper has been accepted by AAAI 2026. And in the near future we'll release the latest paper and a 6.7M dataset, which will be the largest dataset in the field.

2025/02/11: Update the download link and fixed the bug. Note that we uploaded the ID of Pair1 in the original dataset to path 'data/sampled_dataset_uuid.zip'. Due to copyright restrictions, We can't provide these videos directly. You can select the corresponding video from these three data sets Vript/HD-VG-130M/VidProM based on these IDs. 

2025/01/25: The training code is released.

Instruction
---
![微信截图_20240908221413](https://github.com/user-attachments/assets/8e34a3fe-5dfa-4424-8657-7290d5a0248a)

The rapid advancement of video generation models has made it increasingly challenging to distinguish AI-generated videos from real ones. This issue underscores the urgent need for effective AI-generated video detectors to prevent the dissemination of false information through such videos. However, the development of high-performance generative video detectors is currently impeded by the lack of large-scale, high-quality datasets specifically designed for generative video detection. 
To this end, we introduce GenVidBench, a challenging AI-generated video detection dataset with several key advantages: 
1) A huge volume of videos: The dataset contains 6.78 million videos and is currently the largest dataset for AI-generated video detection.
2) Cross-Source and Cross-Generator: The cross-generation source reduces the interference of video content on the detection. The cross-generator ensures diversity in video attributes between the training and test sets, preventing them from being overly similar.
3) State-of-the-Art Video Generators: The dataset includes videos from 11 state-of-the-art AI video generators, ensuring that it covers the latest advancements in the field of video generation. These generators ensure that the dataset is not only large but also diverse, aiding in the development of more generalized and effective detection models.

We conduct a comprehensive evaluation of different advanced video generators and present a challenging setting. Additionally, we present rich experimental results including advanced video classification models as baselines. With the GenVidBench, researchers can efficiently develop and evaluate AI-generated video detection models. 
<img width="1704" height="744" alt="data_sum" src="https://github.com/user-attachments/assets/54058a77-77bc-42a6-9a31-aef60ee7c4cc" />

## Results
<img width="1693" height="551" alt="result_6m" src="https://github.com/user-attachments/assets/00419f03-7068-4e02-9226-e15c58e116e4" />

<img width="600" height="400" alt="f1" src="https://github.com/user-attachments/assets/4de33683-160e-4966-8a95-6fca39cfc869" />

<img width="640" height="360" alt="results_143k" src="https://github.com/user-attachments/assets/4bd9bba3-1d75-46ed-bbe0-9f7c2d5863a6" />


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=genvidbench/GenVidBench&type=date&legend=top-left)](https://www.star-history.com/#genvidbench/GenVidBench&type=date&legend=top-left)

License
---
CC BY-NC 4.0



