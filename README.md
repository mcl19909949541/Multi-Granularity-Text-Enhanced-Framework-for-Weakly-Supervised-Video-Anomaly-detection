# Multi-Granularity-Text-Enhanced-Framework-for-Weakly-Supervised-Video-Anomaly-detection

🎉 ​​Official PyTorch website​​ of our CVIDL 2025 Best Paper Award winner: "Multi-Granularity Text Enhanced Framework for Weakly Supervised Video Anomaly Detection via Cross-Modal Context Alignment".

This repository contains the code and models for our innovative framework that leverages multi-granularity text information (coarse-grained label text and fine-grained description text) to enhance visual feature learning for Weakly Supervised Video Anomaly Detection (WSVAD).

[[Paper Link]](https://doi.org/10.1109/CVIDL65390.2025.11085428)


## 📖 Overview
Weakly Supervised Video Anomaly Detection (WSVAD) aims to identify anomalous events in videos using only video-level labels, significantly reducing annotation costs. However, most existing methods rely solely on visual information, neglecting the rich semantic context available in textual descriptions.

To bridge this gap, we propose a novel framework that integrates ​​multi-granularity text information​​ to boost the semantic understanding of visual features:

​​Coarse-grained label text​​: Provides broad semantic information about anomaly categories

​​Fine-grained description text​​: Contains specific context details of anomaly events

​​Temporal Enhanced Module​​: Captures both local and global temporal dependencies

​​Cross-modal alignment​​: Establishes semantic associations between vision and text

## Citation

If you find our work useful in your research, please consider citing: 

```
@INPROCEEDINGS{11085428,
  author={Meng, Chenlin and Wang, Xin and Shen, Junge and Mao, Zhaoyong},
  booktitle={2025 6th International Conference on Computer Vision, Image and Deep Learning (CVIDL)}, 
  title={Multi-Granularity Text Enhanced Framework for Weakly Supervised Video Anomaly Detection Via Cross-Modal Context Alignment}, 
  year={2025},
  volume={},
  number={},
  pages={764-767},
  abstract={With the increasing prevalence of surveillance devices, automatic detection of anomalies in videos has gained significant importance. However, traditional methods tend to utilize only visual information while often neglecting the substantial expressive potential of textual data. To address this limitation, this study proposes an innovative framework that improves the detection performance by simultaneously leveraging both coarse-grained label text and fine-grained description text to enhance vision information. Specifically, our framework consists of three core components: the temporal enhanced module to capture local and global temporal dependencies of the video, the label enhanced module to establish high-level semantic associations using label text, and the description enhanced module to achieve fine-grained contextual alignment using description text. Experimental results on the UCF-Crime and XD-Violence datasets demonstrate that our approach achieves excellent performance, thereby validating its efficacy in accurately detecting anomalous events within complex scenarios.},
  keywords={Performance evaluation;Deep learning;Visualization;Computer vision;Weak supervision;Surveillance;Semantics;Anomaly detection;Videos;Anomaly Detection;Weak Supervision;Multimodal framework},
  doi={10.1109/CVIDL65390.2025.11085428},
  ISSN={},
  month={May},}
```
