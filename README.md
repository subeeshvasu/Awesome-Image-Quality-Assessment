# Awesome Image Quality Assessment (IQA)
A comprehensive collection of IQA papers, datasets and codes. We also provide PyTorch implementations of mainstream metrics in [IQA-PyTorch](https://github.com/chaofengc/IQA-PyTorch) 

- [Awesome Image Quality Assessment (IQA)](#awesome-image-quality-assessment-iqa)
  - [Papers](#papers)
    - [No Reference (NR)](#no-reference-nr)
    - [Full Reference (FR)](#full-reference-fr)
    - [Image Aesthetic Assessment](#image-aesthetic-assessment)
    - [Others](#others)
  - [Datasets](#datasets)
    - [IQA datasets](#iqa-datasets)
    - [Perceptual similarity datasets](#perceptual-similarity-datasets)
  
Related Resources:
- [Awesome Image Aesthetic Assessment and Cropping](https://github.com/bcmi/Awesome-Aesthetic-Evaluation-and-Cropping). A curated list of resources including papers, datasets, and relevant links to aesthetic evaluation and cropping.

## Papers

### No Reference (NR)
- `[CVPR2023]` [Re-IQA: Unsupervised Learning for Image Quality Assessment in the Wild](https://arxiv.org/abs/2304.00451), Saha et al. [Bibtex](./iqa_ref.bib#L791-L796)
- `[CVPR2023]` [Blind Image Quality Assessment via Vision-Language Correspondence: A Multitask Learning Perspective](https://arxiv.org/abs/2303.14968), Zhang et al. [Github](https://github.com/zwx8981/LIQE) | [Bibtex](./iqa_ref.bib#L770-L775)
- `[CVPR2023]` [Quality-aware Pre-trained Models for Blind Image Quality Assessment](https://arxiv.org/abs/2303.00521), Zhao et al. [Bibtex](./iqa_ref.bib#L763-L768)
- `[AAAI2023]` [Exploring CLIP for Assessing the Look and Feel of Images](https://arxiv.org/abs/2207.12396), Wang et al. [Github](https://github.com/IceClear/CLIP-IQA) | [Bibtex](./iqa_ref.bib#L745-L750)
- `[AAAI2023]` [Data-Efficient Image Quality Assessment with Attention-Panel Decoder](https://arxiv.org/abs/2304.04952), Qin et al. [Github](https://github.com/narthchin/DEIQT) | [Bibtex](./iqa_ref.bib#L745-L750)



| Paper Link | Method | Type | Published | Code | Keywords | 
| ----------- | ---------- | ------------| ---------- | ------ | ------ |
| [arXiv](https://ieeexplore.ieee.org/document/9694502) | | NR | TIP2022 | [Official](https://github.com/NUIST-Videocoding/VCRNet) | VCRNet: Visual Compensation Restoration Network for No-Reference Image Quality Assessment |
| [arXiv](https://arxiv.org/abs/2103.07666) | | NR | TMM2022 | [Official](https://github.com/geekyutao/GraphIQA) | GraphIQA: Learning Distortion Graph Representations for Blind Image Quality Assessment |
| [arXiv](https://arxiv.org/abs/2102.09717) | | NR | TPAMI2022 | [Official](https://github.com/zwx8981/BIQA_CL) | Continual Learning for Blind Image Quality Assessment |
| [arXiv](https://arxiv.org/pdf/2205.13847.pdf) | NRIQA | NR | 2022 | [Official](https://github.com/yuqing-liu-dut/nriqa_sr) | Textural-Perceptual Joint Learning for No-Reference Super-Resolution Image Quality Assessment|
| [arXiv](https://arxiv.org/pdf/2110.13266.pdf) | CONTRIQUE | NR | TIP2022 |  | Image quality assessment using contrastive learning |
| [arXiv](https://arxiv.org/abs/2204.08958) | MANIQA | NR | CVPRW2022 | [Official](https://github.com/IIGROUP/MANIQA) | Transformer, multi-dimension attention, dual branch |
| [arXiv](https://openaccess.thecvf.com/content/WACV2022W/VAQ/papers/Madhusudana_Image_Quality_Assessment_Using_Synthetic_Images_WACVW_2022_paper.pdf) |  | NR | WACV2022 |  | Image Quality Assessment using Synthetic Images |
| [arXiv](https://arxiv.org/abs/2108.06858) | TReS | NR | WACV2022 | [Official](https://github.com/isalirezag/TReS) | Transformer, relative ranking, self-consistency: No-Reference Image Quality Assessment via Transformers, Relative Ranking, and Self-Consistency |
| [pdf](https://arxiv.org/pdf/2101.01097.pdf) | TRIQ | NR | ICIP2021 | [Tf](https://github.com/junyongyou/triq) | Transformer for image quality assessment |
| [pdf](https://arxiv.org/pdf/2111.07104.pdf) | | NR | 2021 | [Tf](https://github.com/Tencent/CenseoQoE) | A strong baseline for image and video quality assessment |
| [pdf](https://www.bmvc2021-virtualconference.com/assets/papers/0868.pdf) | KonIQ++ | NR | BMVC2021 | [Official](https://github.com/SSL92/koniqplusplus) | Multi-task with distortion prediction |
| [arXiv](https://arxiv.org/abs/2108.05997) | MUSIQ | NR | ICCV2021 | [Official](https://github.com/google-research/google-research/tree/master/musiq) / [Pytorch](https://github.com/anse3832/MUSIQ) | Multi-scale, transformer, Aspect Ratio Preserved (ARP) resizing
| [arXiv](https://arxiv.org/abs/2108.07948) | CKDN | NR | ICCV2021 | [Official](https://github.com/researchmm/CKDN) | Degraded reference, Conditional knowledge distillation (related to HIQA)
| [arXiv](https://arxiv.org/pdf/2102.00155.pdf) | | NR | ICASSP2021 |  | Regression or classification? New methods to evaluate no-reference picture and video quality models |
| [pdf](https://arxiv.org/abs/2105.06747) |  | NR | CVPR2021 |  | [git](https://github.com/wangzhihua520/troubleshooting_BIQA) | Troubleshooting Blind Image Quality Models in the Wild |
| [pdf](https://arxiv.org/pdf/2006.03783.pdf) |  | NR | Arxiv2020 |  | No-Reference Image Quality Assessment via Feature Fusion and Multi-Task Learning |
| [pdf](https://www.researchgate.net/publication/339988893_No-Reference_Image_Quality_Assessment_Based_on_Dual-Domain_Feature_Fusion#fullTextFileContent) |  | NR | Arxiv2020 |  | No-Reference Image Quality Assessment Based on Dual-Domain Feature Fusion |
| [pdf](https://ieeexplore.ieee.org/document/8576582) |  | NR | TCSVT2020 | [Pytorch](https://github.com/zwx8981/DBCNN) | Blind image quality assessment using a deep bilinear convolutional neural network |
| [pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Su_Blindly_Assess_Image_Quality_in_the_Wild_Guided_by_a_CVPR_2020_paper.pdf) | HyperIQA | NR | CVPR2020 | [Official](https://github.com/SSL92/hyperIQA) | Content-aware hyper network 
| [arXiv](https://arxiv.org/abs/2004.05508) | Meta-IQA | NR | CVPR2020 | [Official](https://github.com/zhuhancheng/MetaIQA) | Meta-learning |
| [arXiv](https://arxiv.org/abs/1912.10088) | PaQ-2-PiQ | NR | CVPR2020 | [Official](https://github.com/baidut/PaQ-2-PiQ) | From Patches to Pictures (PaQ-2-PiQ): Mapping the Perceptual Space of Picture Quality |
| [arXiv](https://arxiv.org/abs/2003.08932) | GIQA | NR | ECCV2020 | [Official](https://github.com/cientgu/GIQA) | Generated image 
| [arXiv](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9159559) | | NR | Access2020 |  | Blind image quality assessment for super resolution via optimal feature selection
| [arXiv](https://arxiv.org/pdf/1902.06285.pdf) | | NR | TPAMI2019 |  | Exploiting unlabeled data in cnns by self-supervised learning to rank
| [arXiv](https://ieeexplore.ieee.org/abstract/document/8833510) | | NR | TIP2019 |  |Quality measurement of images on mobile streaming interfaces deployed at scale
| [arXiv](https://ieeexplore.ieee.org/abstract/document/8682512) | | NR | ICASSP2019 |  | Optimal feature selection for blind super-resolution image quality evaluation
| [arXiv](https://arxiv.org/abs/1809.07517) | PI | NR | 2018 PIRM Challenge | [Project](https://github.com/roimehrez/PIRM2018) | 1/2 * (NIQE + (10 - NRQM)). 
| [arXiv](https://drive.google.com/file/d/1UwmhqcMpGKAO1up1ykyAOay9vLau5ilh/view) | | NR | ICIP2018 |  | Blind image quality assessment with a probabilistic quality representation
| [arXiv](https://arxiv.org/abs/1804.01681) | HIQA | NR | CVPR2018 | [Project](https://kwanyeelin.github.io/projects/HIQA/HIQA.html) | Hallucinated reference 
| [arXiv](https://arxiv.org/pdf/1805.08493v1.pdf) | BPSQM | NR | CVPR2018 | []() | Pixel-wise quality map 
| [arXiv](https://arxiv.org/abs/1707.08347) | RankIQA | NR | ICCV2017 | [Github](https://github.com/xialeiliu/RankIQA) | Pretrain on synthetically ranked data 
| [arXiv](https://arxiv.org/pdf/1708.08190.pdf) |  | NR | 2017 | | A probabilistic quality representation approach to deep blind image quality prediction
| [pdf](https://openaccess.thecvf.com/content_cvpr_2014/papers/Kang_Convolutional_Neural_Networks_2014_CVPR_paper.pdf) | CNNIQA | NR | CVPR2014 | [PyTorch](https://github.com/lidq92/CNNIQA) | First CNN-based NR-IQA 
| []() | | | | []() | 
| [arXiv](https://arxiv.org/abs/2005.13983) | UNIQUE | NR | TIP2021 | [Github](https://github.com/zwx8981/UNIQUE) | Combine synthetic and authentic image pairs 
| [arXiv](https://arxiv.org/pdf/1907.02665.pdf) | DBCNN | NR | TCSVT2020 | [Official](https://github.com/zwx8981/DBCNN-PyTorch) | Two branches for synthetic and authentic distortions 
| [pdf](http://www.jdl.link/doc/2011/20191226_08489929.pdf) | SFA | NR | TMM2019 | [Official](https://github.com/lidq92/SFA) | Aggregate ResNet50 features of multiple cropped patches
| [pdf](https://drive.google.com/file/d/1tMjcllKP8SzTn-dWVmogxaCLpzL1L7nO/view)/[arXiv](https://arxiv.org/abs/1708.08190) | PQR | NR/Aesthetic | TIP2019 | [Official1](https://github.com/HuiZeng/Unified_IAA)/[Official2](https://github.com/HuiZeng/BIQA_Toolbox) | Unify different type of aesthetic labels 
| [pdf](https://ieeexplore.ieee.org/abstract/document/8462363) |  | NR | ICASSP2018 |  | Second order natural scene statistics model of blind image quality assessment
| [arXiv](https://arxiv.org/abs/1612.01697) | WaDIQaM (deepIQA) | NR/FR | TIP2018 | [PyTorch](https://github.com/lidq92/WaDIQaM) | Weighted average of patch qualities, shared FR/NR models 
| [pdf](https://ieeexplore.ieee.org/ielx7/83/8347140/08352823.pdf) | NIMA | NR | TIP2018 | [PyTorch](https://github.com/kentsyx/Neural-IMage-Assessment)/[Tensorflow](https://github.com/idealo/image-quality-assessment) | Squared EMD loss 
| [pdf](https://ece.uwaterloo.ca/~z70wang/publications/TIP_E2E_BIQA.pdf) | MEON | NR | TIP2017 | | Multi-task: distortion learning and quality prediction
| [arXiv](https://arxiv.org/abs/1904.06505) | dipIQ | NR | TIP2017 | [download](https://ece.uwaterloo.ca/~k29ma/codes/dipIQ.rar) | Similar to RankIQA
| []() | | | | []() | 
| [arXiv](https://arxiv.org/abs/1612.05890) | NRQM (Ma) | NR | CVIU2017 | [Project](https://sites.google.com/site/chaoma99/sr-metric) | Traditional, Super resolution 
| [arXiv](https://arxiv.org/abs/1609.04757) | FRIQUEE | NR | JoV2017 | [Official](https://github.com/utlive/FRIQUEE) | Authentically Distorted, Bag of Features
| [IEEE](https://ieeexplore.ieee.org/document/7501619) | HOSA | NR | TIP2016 | [Matlab download](https://ieeexplore.ieee.org/document/7501619) | Traditional 
| [pdf](https://live.ece.utexas.edu/publications/2015/zhang2015feature.pdf) | ILNIQE | NR | TIP2015 | [Official](http://www4.comp.polyu.edu.hk/~cslzhang/IQA/ILNIQE/ILNIQE.htm) | Traditional 
| [pdf](https://drive.google.com/file/d/1F4dZ7-v3qtbN7-MRA-eWrOZYcyzfxF1Z/view) | SSEQ | NR | SPIC2014 | [Matlab](https://github.com/OaDsis/No-Reference-IQA) | Trad: No-reference image quality assessment based on spatial and spectral entropies
| [pdf](https://gfx.cs.princeton.edu/pubs/Liu_2013_ANM/sa13.pdf) | | NR | TOG2013 |  | A No-Reference Metric for Evaluating the Quality of Motion Deblurring
| [pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Xue_Learning_without_Human_2013_CVPR_paper.pdf) | | NR | CVPR2013 | [Matlab](http://www4.comp.polyu.edu.hk/~cslzhang/code/QAC.zip) | Learning without human scores for blind image quality assessment |
| [pdf](https://live.ece.utexas.edu/publications/2012/TIP%20BRISQUE.pdf) | BRISQUE | NR | TIP2012 | [Official](https://github.com/utlive/BRISQUE) | Traditional 
| [pdf](https://live.ece.utexas.edu/publications/2012/saad_2012_tip.pdf) | BLIINDS-II | NR | TIP2012 | [Official](https://github.com/utlive/BLIINDS2) | Blind Image Quality Assessment: A Natural Scene Statistics Approach in the DCT Domain
| [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.359.7510&rep=rep1&type=pdf) | CORNIA | NR | CVPR2012 | [Matlab download](https://github.com/HuiZeng/BIQA_Toolbox) | Codebook Representation 
| [pdf](https://live.ece.utexas.edu/publications/2013/mittal2013.pdf) | NIQE | NR | SPL2012 | [Official](https://github.com/utlive/niqe) | Traditional 
| [pdf](https://www.imaging.utk.edu/research/wcho/references/2011%20TIP%20BLINDS2.pdf) | DIIVINE | NR | TIP2011 | [Official](https://github.com/utlive/DIIVINE) | 
| [pdf](https://ieeexplore.ieee.org/document/5432998) | BIQI | NR | SPL2010 | [Matlab](https://github.com/dsoellinger/blind_image_quality_toolbox) | Trad: A Two-Step Framework for Constructing Blind Image Quality Indices
| [pdf](https://hal.science/file/index/docid/808353/filename/ms_spl_june10.pdf) |  | NR | SPL2010 | | Trad: A DCT statistics-based blind image quality index
| [pdf](https://www.sciencedirect.com/science/article/abs/pii/S0165168407003337) |  | NR | SP2008 |  | Trad: No-reference image quality assessment based on DCT domain statistics
<!-- | []() | | NR | | []() |  -->

### Full Reference (FR)


- `[ECCV2022]` [Shift-tolerant Perceptual Similarity Metric](https://arxiv.org/abs/2211.052152207.13686), Ghildyal et al. [Github](https://github.com/abhijay9/ShiftTolerant-LPIPS) | [Bibtex](./iqa_ref.bib#L731-L736)
- `[BMVC2022]` [Content-Diverse Comparisons improve IQA](https://arxiv.org/abs/2211.05215), Thong et al. [Bibtex](./iqa_ref.bib#L724-L729)
- `[ACM MM2022]` [Quality Assessment of Image Super-Resolution: Balancing Deterministic and Statistical Fidelity](https://arxiv.org/abs/2207.08689), Zhou et al. [Github](https://github.com/weizhou-geek/SRIF) | [Bibtex](./iqa_ref.bib#L709-L714)

| Paper Link | Method | Type | Published | Code | Keywords | 
| ----------- | ---------- | ------------| ---------- | ------ | ------ |
| [arXiv](https://arxiv.org/abs/2204.10485) | AHIQ | FR | CVPR2022 NTIRE workshop | [Official](https://github.com/IIGROUP/AHIQ) | Attention, Transformer
| [arXiv](https://arxiv.org/abs/2204.08763) | JSPL | FR | CVPR2022 | [Official](https://github.com/happycaoyue/JSPL) | semi-supervised and positive-unlabeled (PU) learning |
| [arXiv](https://arxiv.org/abs/2202.13123) | CVRKD | NAR | AAAI2022 | [Official](https://github.com/guanghaoyin/CVRKD-IQA) | Non-Aligned content reference, knowledge distillation 
| [arXiv](https://arxiv.org/abs/2104.14730) | IQT | FR | CVPRW2021 | [PyTorch](https://github.com/anse3832/IQT) | Transformer 
| [arXiv](https://arxiv.org/abs/2110.08521) | A-DISTS | FR | ACMM2021 | [Official](https://github.com/dingkeyan93/A-DISTS) | 
| [arXiv](https://arxiv.org/abs/2004.07728) | DISTS | FR | TPAMI2021 | [Official](https://github.com/dingkeyan93/DISTS) | 
| [arXiv](https://arxiv.org/abs/1801.03924) | LPIPS | FR | CVPR2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | Perceptual similarity, Pairwise Preference 
| [arXiv](https://arxiv.org/abs/1806.02067) | PieAPP | FR | CVPR2018 | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | Perceptual similarity, Pairwise Preference 
| [arXiv](https://arxiv.org/abs/1612.01697) | WaDIQaM | NR/FR | TIP2018 | [Official](https://github.com/lidq92/WaDIQaM) | 
| [arXiv](https://arxiv.org/abs/1902.05316) | JND-SalCAR | FR| TCSVT2020 | []() | JND (Just-Noticeable-Difference) 
| []() | | | | []() | 
| [pdf](https://nottingham-repository.worktribe.com/preview/1589753/Visual%20IEEE-TIP-2019.pdf) | QADS | FR | TIP2019 | [Project](http://www.vista.ac.cn/super-resolution/) | Super-resolution 
| [pdf](https://sse.tongji.edu.cn/linzhang/IQA/FSIM/Files/Fsim%20a%20feature%20similarity%20index%20for%20image%20quality%20assessment.pdf) | FSIM | FR | TIP2011 | [Project](https://sse.tongji.edu.cn/linzhang/IQA/FSIM/FSIM.htm) | Traditional 
| [pdf](https://live.ece.utexas.edu/publications/2004/hrs_ieeetip_2004_imginfo.pdf) | VIF | FR | TIP2006 | [Project](https://live.ece.utexas.edu/research/Quality/VIF.htm) | Traditional 
| [pdf](https://live.ece.utexas.edu/publications/2004/hrs_ieeetip_2004_imginfo.pdf) | IFC | FR | TIP2005 | [Project](https://live.ece.utexas.edu/research/Quality/VIF.htm) | Traditional 
| [pdf](https://ece.uwaterloo.ca/~z70wang/publications/msssim.pdf) | MS-SSIM | FR | | [Project](https://ece.uwaterloo.ca/~z70wang/research/ssim/) | Traditional 
| [pdf](https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf) | SSIM | FR | TIP2004 | [Project](https://ece.uwaterloo.ca/~z70wang/research/ssim/) | Traditional 
| []() | PSNR | FR | | []() | Traditional 
<!-- | []() | | FR | | []() |  -->

### Image Aesthetic Assessment 

- `[CVPR2023]` [VILA: Learning Image Aesthetics from User Comments with Vision-Language Pretraining](https://arxiv.org/abs/2303.14302), Ke et al. [Bibtex](./iqa_ref.bib#L784-L789)
- `[CVPR2023]` [Towards Artistic Image Aesthetics Assessment: a Large-scale Dataset and a New Method](https://arxiv.org/abs/2303.14968), Yi et al. [Github](https://github.com/Dreemurr-T/BAID) | [Bibtex](./iqa_ref.bib#L777-L782)

### Others 

| Title | Method | Published | Code | Keywords | 
| ----------- | ------------| ---------- | ------ | ------ |
| [arXiv](https://arxiv.org/abs/2008.03889) | NiNLoss | ACMM2020 | [Official](https://github.com/lidq92/LinearityIQA) | Norm-in-Norm Loss | 
| [arXiv]() |  |  | [Pytorch-Code](https://github.com/chaofengc/IQA-PyTorch) | How to evaluate IQ metrics | 

## Datasets 

### IQA datasets

| Paper Link | Dataset Name | Type | Published | Website | Images | Annotations
| ----------- | ---------- | ------------| ---------- | ------ | ------ |------ |
| [arXiv](https://arxiv.org/abs/1912.10088) | PaQ-2-PiQ | NR | CVPR2020 | [Official github](https://github.com/baidut/PaQ-2-PiQ) | 40k, 120k patches | 4M |
| [CVF](https://openaccess.thecvf.com/content_CVPR_2020/html/Fang_Perceptual_Quality_Assessment_of_Smartphone_Photography_CVPR_2020_paper.html)  | SPAQ | NR | CVPR2020 | [Offical github](https://github.com/h4nwei/SPAQ) | 11k (smartphone) | |  
| [arXiv](https://arxiv.org/abs/1910.06180) | KonIQ-10k | NR | TIP2020 | [Project](http://database.mmsp-kn.de/koniq-10k-database.html) | 10k from [YFCC100M](http://projects.dfki.uni-kl.de/yfcc100m/) | 1.2M | 
| [arXiv](https://arxiv.org/abs/1511.02919) | CLIVE | NR | TIP2016 | [Project](https://live.ece.utexas.edu/research/ChallengeDB/index.html) | 1200 | 350k |
| [pdf](http://refbase.cvc.uab.es/files/MMP2012a.pdf) | AVA | NR / Aesthentic | CVPR2012 | [Github](https://github.com/mtobeiyf/ava_downloader)/[Project](http://www.lucamarchesotti.com/) | 250k (60 categories) | | 
| [arXiv](https://arxiv.org/abs/2007.12142) | PIPAL | FR | ECCV2020 | [Project](https://www.jasongt.com/projectpages/pipal.html) | 250 | 1.13M |
| [arXiv](https://arxiv.org/abs/2001.08113) | KADIS-700k | FR | arXiv | [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | 140k pristine / 700k distorted | 30 ratings (DCRs) per image. | 
| [IEEE](https://ieeexplore.ieee.org/document/8743252) | KADID-10k | FR | QoMEX2019 | [Project](http://database.mmsp-kn.de/kadid-10k-database.html) | 81 | 10k distortions |
| [pdf](https://ece.uwaterloo.ca/~k29ma/papers/17_TIP_EXPLORATION.pdf) | Waterloo-Exp | FR | TIP2017 | [Project](https://ece.uwaterloo.ca/~k29ma/exploration/) | 4744 | 94k distortions | 
| [pdf](https://daneshyari.com/article/preview/533080.pdf) | MDID | FR | PR2017 | --- | 20 | 1600 distortions  |
| [pdf](http://www.ponomarenko.info/papers/euvip_tid2013.pdf) | TID2013 | FR | SP2015 | [Project](http://www.ponomarenko.info/tid2013.htm) | 25 | 3000 distortions |
| [pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.298.9133&rep=rep1&type=pdf)  | LIVEMD | FR | ACSSC2012 | [Project](https://live.ece.utexas.edu/research/Quality/live_multidistortedimage.html) | 15 pristine images | two successive distortions |
| [pdf](https://www.researchgate.net/profile/Damon-Chandler/publication/220050520_Most_apparent_distortion_Full-reference_image_quality_assessment_and_the_role_of_strategy/links/5629cd1c08ae518e347e1445/Most-apparent-distortion-Full-reference-image-quality-assessment-and-the-role-of-strategy.pdf)  | CSIQ | FR | Journal of Electronic Imaging 2010 | --- | 30 | 866 distortions |
| [pdf](http://www.ponomarenko.info/papers/mre2009tid.pdf) | TID2008 | FR | 2009 | [Project](http://www.ponomarenko.info/tid2008.htm) | 25 | 1700 distortions |
| [pdf](https://live.ece.utexas.edu/publications/2006/hrs-transIP-06.pdf) | LIVE IQA | FR | TIP2006 | [Project](https://live.ece.utexas.edu/research/Quality/subjective.htm) | 29 images, 780 synthetic distortions 
| [link](http://hal.univ-nantes.fr/hal-00580755/) | IVC | FR | 2005 | --- | 10 | 185 distortions |

### Perceptual similarity datasets

| Paper Title | Dataset Name | Type | Published | Website | Images | Annotations |  
| ----------- | ---------- | ------------| ---------- | ------ | ------ | ----- |
| [arXiv](https://arxiv.org/abs/1801.03924) | BAPPS(LPIPS) | FR | CVPR2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | 187.7k  | 484k 
| [arXiv](https://arxiv.org/abs/1806.02067) | PieAPP | FR | CVPR2018 | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/) | 200 images | 2.3M 
