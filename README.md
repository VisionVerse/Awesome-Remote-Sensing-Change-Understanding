# Awesome Remote Sensing Change Detection
An awesome repository for remote sensing change detection, covering papers, datasets, benchmarks, foundation models, and AI agents.


## 💥: Update Log 
* [2024.12.17] We update the criterion for taxonomy and also invovle newly published methods.
* [2026.7.10] The repository is started.


## :punch: : Find what you want quickly

[Remote Sensing Change Detection](#RGB-T-Tracking)



## :punch: :Datasets and Benchmarks

### RGB-Mutli Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| QuadTrack600| Arxiv'2025 |[QuadTrack600]() |RGB+T+E+L: Towards General Multimodal Visual Tracking|
| UniMod1K| IJCV'2024 |[UniMod1K](https://github.com/xuefeng-zhu5/UniMod1K) |RGB+D+L: UniMod1K: Towards a More Universal Large-Scale Dataset and Benchmark for Multi-modal Learning|
| WebUAV-3M| TPAMI'2023 | [WebUAV-3M](https://github.com/983632847/WebUAV-3M) | RGB+L+Audio: WebUAV-3M: A Benchmark for Unveiling the Power of Million-Scale Deep UAV Tracking|



### RGBT Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| MV-RGBT| Arxiv'2024 |MV-RGBT |Revisiting RGBT Tracking Benchmarks from the Perspective of Modality Validity: A New Benchmark, Problem, and Method|



### RGBD Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| D2CUBE| CVRP'2023|[D2CUBE](https://github.com/yjybuaa/RGBDAerialTracking)|Resource-Efficient RGBD Aerial Tracking|


### RGBE Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| CRSOT| Arxiv'2024 |[CRSOT](https://github.com/Event-AHU/Cross_Resolution_SOT) |CRSOT: Cross-Resolution Object Tracking using Unaligned Frame and Event Cameras|
| FELT| Arxiv'2024 |[FELT](https://github.com/Event-AHU/FELT_SOT_Benchmark) |Long-term Frame-Event Visual Tracking: Benchmark Dataset and Baseline|
| FE141| IJCV'2024 | [FE141](https://zhangjiqing.com/publication/ijcv2023/)|A Universal Event-Based Plug-In Module for Visual Object Tracking in Degraded Conditions|
| FE240hz| CVPR'2023 | [FE240hz](https://zhangjiqing.com/publication/frame-event-alignment-and-fusion-network-for-high-frame-rate-tracking/)|Frame-Event Alignment and Fusion Network for High Frame Rate Tracking|
| COESOT| Arxiv'2022 | [COESOT](https://github.com/Event-AHU/COESOT)|Revisiting Color-Event based Tracking: A Unified Network, Dataset, and Metric|
| VisEvent| TCYB'2023 |[VisEvent](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark?tab=readme-ov-file)|VisEvent: Reliable Object Tracking via Collaboration of Frame and Event Flows|
| FE108| ICCV'2021 | [FE108/FE240hz](https://github.com/Jee-King/ICCV2021_Event_Frame_Tracking)|Object Tracking by Jointly Exploiting Frame and Event Domain|
| EED| Arxiv'2018 | [EED](http://prg.cs.umd.edu/BetterFlow.html)|Event-based Moving Object Detection and Tracking|



### RGBL Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| UW-COT220| Arxiv'2025 |[UW-COT220](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Underwater+Camouflaged+Object+Tracking+Meets+Vision-Language+SAM2&btnG=) |Underwater Camouflaged Object Tracking Meets Vision-Language SAM2|
| DTVLT| Arxiv'2024 |[DTVLT](http://videocube.aitestunion.com/downloads) |DTVLT: A Multi-Modal Diverse Text Benchmark For Visual Language Tracking Based On LLM|
| VLT-MI| Arxiv'2024 |VLT-MI |Visual Language Tracking with Multi-modal Interaction: A Robust Benchmark|
| ElysiumTrack-1M| Arxiv'2024 |[ElysiumTrack-1M](https://github.com/Hon-Wong/Elysium) |Elysium: Exploring Object-level Perception in Videos via MLLM|
| WebUOT-1M| Arxiv'2024 |[WebUOT-1M](https://github.com/983632847/Awesome-Multimodal-Object-Tracking) |WebUOT-1M: Advancing Deep Underwater Object Tracking with A Million-Scale Benchmark|
| VastTrack| Arxiv'2024 |[VastTrack](https://github.com/HengLan/VastTrack) |VastTrack: Vast Category Visual Object Tracking|
| MGIT| NIPS'2023 |[MGIT](http://videocube.aitestunion.com/) |A Multi-modal Global Instance Tracking Benchmark (MGIT): Better Locating Target in Complex Spatio-temporal and Causal Relationship|
| TNL2K| CVPR'2021 | [TNL2K](https://github.com/wangxiao5791509/TNL2K_evaluation_toolkit)|Towards More Flexible and Accurate Object Tracking with Natural Language: Algorithms and Benchmark|
| LaSOT_EXT| IJCV'2021 |[LaSOT_EXT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)|LaSOT: A High-quality Large-scale Single Object Tracking Benchmark|
| LaSOT| CVPR'2019 | [LaSOT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)|LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking|
| OTB99-L| CVPR'2017 | [OTB99-L](https://github.com/QUVA-Lab/lang-tracker) |Tracking by Natural Language Specification|


## :star2: :Surveys and Report
* RGBD/T/L/Lidar ---- Visual Object Tracking across Diverse Data Modalities: A Review. Mengmeng Wang, Teli Ma, Shuo Xin, Xiaojun Hou, Jiazheng Xing, Guang Dai, Jingdong Wang, and Yong Liu. [[Paper](Arxiv 2024. https://arxiv.org/abs/2412.09991)]



## :star: :Regular Papers 

### Unified (Model or Architecture for) Multi-Modal Tracking
* Adaptive Perception for Unified Visual Multi-modal Object Tracking. Xiantao Hu, Bineng Zhong, Qihua Liang, Zhiyi Mo, Liangtao Shi, Ying Tai, Jian Yang. TAI 2025. [[paper](https://ieeexplore.ieee.org/abstract/document/10955486/)] [Code] APTrack
* Cross-Modality Distillation for Multi-modal Tracking. Tianlu Zhang, Qiang Zhang, Kurt Debattista, Jungong Han. TPAMI 2025.  [[paper](https://ieeexplore.ieee.org/document/10943265)] [[Code](https://github.com/Tianlu-Zhang/TransCMD)] CMDTrack
* Exploiting Multimodal Spatial-temporal Patterns for Video Object Tracking. Xiantao Hu, Ying Tai, Xu Zhao, Chen Zhao, Zhenyu Zhang, Jun Li, Bineng Zhong, Jian Yang. AAAI 2025. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32372)] [[Code](https://github.com/NJU-PCALab/STTrack.)]. STTrack
* LightFC-X: Lightweight Convolutional Tracker for RGB-X Tracking. Yunfeng Li Bo Wang Ye Li. Arxiv 2025.  [[paper](https://arxiv.org/abs/2502.18143)] [[Code](https://github.com/LiYunfengLYF/LightFC-X)] LightFC-X
* SUTrack: Towards Simple and Unified Single Object Tracking. Xin Chen, Ben Kang, Wanting Geng, Jiawen Zhu, Yi Liu, Dong Wang, Huchuan Lu. AAAI 2025. [[paper](https://arxiv.org/abs/2412.19138)] [[Code](https://github.com/chenxin-dlut/SUTrack)] SUTrack



### Remote Sensing Change Detection
2026
* CADTrack: Learning Contextual Aggregation with Deformable Alignment for Robust RGBT Tracking. Hao Li, Yuhao Wang, Xiantao Hu, Wenning Hao, Pingping Zhang, Dong Wang, Huchuan Lu. AAAI 2026. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/37535)] [[Code](https://github.com/IdolLab/CADTrack)]. CADTrack

2025
* BTMTrack: Robust RGB-T Tracking via Dual-template Bridging and Temporal-Modal Candidate Elimination. Zhongxuan Zhang, Bi Zeng, Xinyu Ni, Yimin Du. Arxiv 2025. [[Paper](https://arxiv.org/abs/2501.03616)] [Code]. BTMTrack
* Breaking Shallow Limits: Task-Driven Pixel Fusion for Gap-free RGBT Tracking. Andong Lu, Yuanzhi Guo, Wanyu Wang, Chenglong Li, Jin Tang, Bin Luo. Arxiv 2025. [[Paper](https://arxiv.org/abs/2503.11247)] [Code]. TPF
* Cross-Modal Stealth: A Coarse-to-Fine Attack Framework for RGB-T Tracker. Xinyu Xiang, Qinglong Yan, Hao Zhang, Jianfeng Ding, Han Xu, Zhongyuan Wang, Jiayi Ma. AAAI 2025. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32931)] [[Code](https://github.com/Xinyu-Xiang/CMS)]. CMS
* Enhanced RGBT Tracking Network with Semantic Generation and Historical Context. Zhao Gao, Dongming Zhou, Jinde Cao, Yisong Liu, Qingqing Shan. TIM 2025.  [[Paper](https://ieeexplore.ieee.org/abstract/document/10925564/)] [Code]. SHT
* FcFNet: A Challenge-Based Feature Complementary Fusion Network for RGBT Tracking. Wensheng Wang, Congjian Li, Di Zhang, Huihui Zhou, Mingli Xie, Haoran Zhou and Kun Fu. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 2025. [[Paper](https://ieeexplore.ieee.org/abstract/document/10803956)] [[Code](https://github.com/saajoejge/FcFNet)]. FcFNet
* IAMTrack: interframe appearance and modality tokens propagation with temporal modeling for RGBT tracking. Huiwei Shi, Xiaodong Mu, Hao He, Chengliang Zhong, Bo Zhang, Peng Zhao. Applied Intelligence 2025. [[Paper](https://link.springer.com/article/10.1007/s10489-025-06438-w)] [Code]. IAMTrack
* MKFTracker: An RGBT tracker via multimodal knowledge embedding and feature interaction. Fangfang Lia, Weidai Xia, Dongming Zhou, Jinde Cao. KBS 2025. [[Paper](https://www.sciencedirect.com/science/article/pii/S0950705124014941)] [Code]. MKFTracker
* Progressive Transformer with Multi-modality Adaptation for RGB-T Tracking. Binxin Luo, Dongxu Liu, Xianrong Peng, Haorui Zuo, Jianlin Zhang, Meihui Li, and Yuxing Wei. IEEE TIM 2025. [[Paper](https://ieeexplore.ieee.org/iel8/19/10764799/11023155.pdf)] [Code]. PTrMA
* TVTracker: Target-Adaptive Text-Guided Visual Fusion for Multi-Modal RGB-T Tracking. Fang Gao, Wenjie Wu, Yan Jin, Jingfeng Tang, Hanbo Zheng, Shengheng Ma, and Jun Yu. IoTJ 2025. [[Paper](https://ieeexplore.ieee.org/abstract/document/10948521)] [Code]. TVTracker
* Two-stage Unidirectional Fusion Network for RGBT tracking. Yisong Liu, Zhao Gao, Yang Cao, Dongming Zhou. KBS 2025. [[Paper](https://www.sciencedirect.com/science/article/pii/S0950705125000310)] [Code]. TUFNet

2024
* FADSiamNet: feature afnity drift siamese network for RGB‑T target tracking. Haiyan Li, Yonghui Cao, Lei Guo, Quan Chen, Zhaisheng Ding, Shidong Xie. IJMLC 2024. [[Paper](https://link.springer.com/article/10.1007/s13042-024-02420-z)] [Code]. JKAKF
* A Lightweight Robust RGB-T Object Tracker Based on Jitter Factor and Associated Kalman Filter. Shuixin Pan , Haopeng Wang , Dilong Li , Yueqiang Zhang ,Bahubali Shiragapur , Xiaolin Liu , Qifeng Yu. Information Fusion 2024.  [[Paper](https://www.sciencedirect.com/science/article/pii/S1566253524006201?casa_token=DAIf-W5KmzAAAAAA:CkibyOkX6UJf5Dzu49_x6lUxqz_7e5UQSmucRHzyXd7cLHK61EpEvRyUzb8xTxt9p4GdR-rNJjw)] [Code]. JKAKF
* AFter: Attention-based Fusion Router for RGBT Tracking. Andong Lu, Wanyu Wang, Chenglong Li, Jin Tang, Bin Luo. Arxiv 2024. [[Paper](https://arxiv.org/abs/2405.02717)] [[Code](https://github.com/Alexadlu/AFter)]. AFter
* A content-aware correlation filter with multi-feature fusion for RGB-T tracking. Feng Zihang, Yan Liping, Bai Jinglan, Xia Yuanqing, and Xiao Bo. Journal of Systems Engineering and Electronics 2024. [[Paper](https://ieeexplore.ieee.org/abstract/document/10530492)] [Code]. CAFF
* AMNet: Learning to Align Multi-modality for RGB-T Tracking. Zhang Tianlu, He Xiaoyi, Jiao Qiang, Zhang Qiang, Han Jungong. TCSVT 2024. [[Paper](https://ieeexplore.ieee.org/abstract/document/10472533)] [Code]. AMNet.
* Breaking Modality Gap in RGBT Tracking: Coupled Knowledge Distillation. Andong Lu, Jiacong Zhao, Chenglong Li, Yun Xiao, Bin Luo. ACMMM 2024. [[Paper](https://openreview.net/forum?id=2jzyYyRqX0)] [[Code](https://github.com/Alexadlu/CKD)]. CKD.
* Bi-directional Adapter for Multi-modal Tracking. Bing Cao, Junliang Guo, Pengfei Zhu, Qinghua Hu. AAAI 2024. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27852)] [[Code](https://github.com/SparkTempest/BAT)]. BAT
* Cross-modulated Attention Transformer for RGBT Tracking. Yun Xiao, Jiacong Zhao, Andong Lu, Chenglong Li, Yin Lin, Bing Yin, Cong Liu. Arxiv 2024. [[Paper](https://arxiv.org/pdf/2408.02222)] [Code]. CAFormer
* Cross Fusion RGB-T Tracking with Bi-directional Adapter. Zhirong Zeng, Xiaotao Liu, Meng Sun, Hongyu Wang, Jing Liu. Arxiv 2024. [[Paper](https://arxiv.org/pdf/2408.16979)] [Code]. CFBT


2022
* Asymmetric Global–Local Mutual Integration Network for RGBT Tracking. Mei Jiatian, Liu Yanyu, Wang Changcheng, Zhou Dongming, Nie Rencan, Cao Jinde. TIM 2022. [[paper](https://ieeexplore.ieee.org/abstract/document/9840392)]  [Code] AGMINet.



2021

* Adaptive Fusion CNN Features for RGBT Object Tracking. Wang, Yong and Wei, Xian and Tang, Xuan and Shen, Hao and Zhang, Huanlong. TITS 2021. [[paper](https://ieeexplore.ieee.org/abstract/document/9426573)]  [Code] AFCF
* Channel Exchanging for RGB-T Tracking. Long Zhao, Meng Zhu, Honge Ren,  Lingjixuan Xue. Sensors 2021.[[paper](https://www.mdpi.com/1424-8220/21/17/5800)]  [Code] CEDiMP



2020

* Cross-Modal Pattern-Propagation for RGB-T Tracking. Chaoqun Wang, Chunyan Xu, Zhen Cui, Ling Zhou, Tong Zhang, Xiaoya Zhang, Jian Yang. CVPR 2020.[[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Cross-Modal_Pattern-Propagation_for_RGB-T_Tracking_CVPR_2020_paper.html)]  [Code] CMPP


2017

* Grayscale-Thermal Object Tracking via Multitask Laplacian Sparse Representation. Chenglong Li, Xiang Sun, Xiao Wang, Lei Zhang, and Jin Tang. TSMCS 2017. [[paper](https://ieeexplore.ieee.org/abstract/document/7822984)]  [Code] MLSR



2016

* Real-Time Grayscale-Thermal Tracking via Laplacian Sparse Representation. Chenglong Li, Shiyi Hu, Sihan Gao, and Jin Tang. MultiMedia Modeling 2016. [[paper](https://link.springer.com/chapter/10.1007/978-3-319-27674-8_6)]  [Code] 

2012

* Fusion tracking in color and infrared images using joint sparse representation. Liu Huaping, Sun Fuchun. Science China Information Sciences 2012. [[paper](https://link.springer.com/article/10.1007/s11432-011-4536-9)]  [Code] JSR 


2011

* Multiple Source Data Fusion via Sparse Representation for Robust Visual Tracking. Wu, Yi and Blasch, Erik and Chen, Genshe and Bai, Li and Ling, Haibin. ICIF 2011. [[paper](https://ieeexplore.ieee.org/abstract/document/5977451)]  [Code] L1-PF


2008

* Thermo-visual feature fusion for object tracking using multiple spatiogram trackers. Conaire C Ó, O’Connor N E, Smeaton A. Machine Vision and Applications 2008. [[paper](https://link.springer.com/article/10.1007/s00138-007-0078-y)]  [Code]


2007

* The Effect of Pixel-Level Fusion on Object Tracking in Multi-Sensor Surveillance Video. N. Cvejic, S. G. Nikolov, H. D. Knowles, A. Łoza, A. Achim, D. R. Bull and C. N. Canagarajah. CVPR 2007. [[paper](https://ieeexplore.ieee.org/abstract/document/4270431)]  [Code]


2006

* Comparison of fusion methods for thermo-visual surveillance tracking. Conaire, C.O. and O'Connor, N.E. and Cooke, E. and Smeaton, A.F. ICIF 2006. [[paper](https://ieeexplore.ieee.org/abstract/document/4085904)]  [[Code]()]
* The influence of multi-sensor video fusion on object tracking using a particle filter. Mihaylova L., Loza A., Nikolov S. G., Lewis J. J., Canga E. -F., Li, J., Dixon T., Canagarajah C. N., Bull D. R. INFORMATIK 2006 [[paper](https://dl.gi.de/items/016d794a-8c54-4445-8eae-f8c78e5283eb)]  [Code]







## 🥇 Competition
 1. [AntiUAV 1st](https://anti-uav.github.io/)
	The first AntiUAV challenge is a multi-modal challenge. It was held in 2020.  The website for the 1st AntiUAV is covered by the newest one. The winner is team 

## ⚓ Awesome Repositories
* [Awesome-Multimodal-Object-Tracking](https://github.com/983632847/Awesome-Multimodal-Object-Tracking)




## Star History

<a href="https://www.star-history.com/?repos=VisionVerse%2FAwesome-ChangeDetection&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=VisionVerse/Awesome-ChangeDetection&type=date&theme=dark&legend=top-left&sealed_token=zz47e4OpJJZyJeUBDvnTZODud4O5arhR61guSVJvkxbrBPK6H1sQ5UyiwIFAUtk8i9SeWgFVm3xUo6vSxLzD2HnidL0oCNQ2DnnsTE7MnFcjkecix2AOQQv8DjePcEWw-8x4177ogqIl1iMDg7cV655nFUdR7FuCW8a1AGuCIoSvCZgyE383LfrV9I39" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=VisionVerse/Awesome-ChangeDetection&type=date&legend=top-left&sealed_token=zz47e4OpJJZyJeUBDvnTZODud4O5arhR61guSVJvkxbrBPK6H1sQ5UyiwIFAUtk8i9SeWgFVm3xUo6vSxLzD2HnidL0oCNQ2DnnsTE7MnFcjkecix2AOQQv8DjePcEWw-8x4177ogqIl1iMDg7cV655nFUdR7FuCW8a1AGuCIoSvCZgyE383LfrV9I39" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=VisionVerse/Awesome-ChangeDetection&type=date&legend=top-left&sealed_token=zz47e4OpJJZyJeUBDvnTZODud4O5arhR61guSVJvkxbrBPK6H1sQ5UyiwIFAUtk8i9SeWgFVm3xUo6vSxLzD2HnidL0oCNQ2DnnsTE7MnFcjkecix2AOQQv8DjePcEWw-8x4177ogqIl1iMDg7cV655nFUdR7FuCW8a1AGuCIoSvCZgyE383LfrV9I39" />
 </picture>
</a>
