# CAS-VSR-S101 (CVPR '24)
**Last updated:** February 13, 2025

<img src="https://github.com/user-attachments/assets/5ee27e92-e127-44ed-b66c-6bca5a69e50e" alt="CAS-VSR-S101" width="360"/>

## Introduction

The [CAS-VSR-S101 database](https://paperswithcode.com/dataset/cas-vsr-s101) is a Chinese Mandarin dataset intended for research related to audio-visual speech, released by the [audio-visual speech understanding team](https://vipl.ict.ac.cn/en/research/speech/) at Visual Information Processing and Learning group, key Intelligent Information Processing Laboratory of Chinese Academy of Sciences. Please refer to the [license agreement](https://github.com/VIPL-Audio-Visual-Speech-Understanding/CAS-VSR-S101/blob/fec539cf3ee7b9a687bdbff00ee5bd2982b5bea2/CAS-VSR-S101-Release%20Agreement.pdf) in this repository and [supplementary materials](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Zhang_ES3_Evolving_Self-Supervised_CVPR_2024_supplemental.pdf) for the ES³ paper for more details.

## Dataset Contents

The dataset includes:
- **Cropped lip sequences:** Cropped lip sequences from the videos.
- **Audio:** Synchronized audio recordings corresponding to the lip sequences.
- **Annotations:** Ground truth transcriptions for each video.
- **Metadata:** Additional information such as speaker identity (host, interviewer or interviewee), gender and whether the speaker speaks canonical Mandarin or dialectal Mandarin.

## Accessing the Dataset

To access the dataset, please scan the signed agreement and send it to [lipreading@vipl.ict.ac.cn](mailto:lipreading@vipl.ict.ac.cn). **Please note that the dataset is only available to universities and research institutes for research purposes only.** Note that the agreement should be signed by **a full-time staff member (usually your advisor).**  Sharing the dataset with others is **not allowed** under the terms of the agreement. For questions or further information, please contact us via e-mail.

## Data Privacy and Security
Due to data privacy concerns, only the lip region of the videos at a resolution of 96x96 pixels is available. Users are expected to comply with all guidelines and not re-distribute the data.

## Citation

If you use this dataset in your research, please cite it using the following BibTeX entries:

```bibtex
@inproceedings{DBLP:conf/cvpr/ZhangYS024,
  author       = {Yuanhang Zhang and
                  Shuang Yang and
                  Shiguang Shan and
                  Xilin Chen},
  title        = {{ES$^3$}: {E}volving Self-Supervised Learning of Robust Audio-Visual
                  Speech Representations},
  booktitle    = {{CVPR}},
  pages        = {27059--27069},
  publisher    = {{IEEE}},
  year         = {2024}
}

@inproceedings{DBLP:conf/fgr/YangZFYWXLSC19,
  author       = {Shuang Yang and
                  Yuanhang Zhang and
                  Dalu Feng and
                  Mingmin Yang and
                  Chenhao Wang and
                  Jingyun Xiao and
                  Keyu Long and
                  Shiguang Shan and
                  Xilin Chen},
  title        = {{LRW-1000:} {A} Naturally-Distributed Large-Scale Benchmark for Lip
                  Reading in the Wild},
  booktitle    = {{FG}},
  pages        = {1--8},
  publisher    = {{IEEE}},
  year         = {2019}
}
```
