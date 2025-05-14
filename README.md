# Awesome-MLLMs-for-Video-Temporal-Grounding [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<h3 align="center">
🔥 <a href="https://arxiv.org/abs/xxxx">A Survey on Video Temporal Grounding with Multimodal Large Language Model</a>
</h3>

<div align="center">
    <p>
    作者信息
    </p>
    <p>
    <img src="resources/VTG-Task.png" alt="VTG Task" style="width:70%; max-width:1100px;"/>
    </p>
</div>

Video Temporal Grounding (VTG) focuses on locating and understanding temporal segments in untrimmed videos based on multimodal queries. Core tasks include **video moment retrieval**, **dense video captioning**, **video highlight detection**, and **temporally grounded video QA**, all requiring fine-grained temporal reasoning.

With the rise of Multimodal Large Language Models (MLLMs), VTG has seen transformative progress. These models bring powerful cross-modal alignment and semantic reasoning abilities, enabling flexible, generalizable solutions across VTG tasks.

This repository aims to serve as a curated reference point for researchers and practitioners interested in advancing the field of video temporal grounding through the lens of large multimodal models.



## News

## Table of Contents

- [Awesome-MLLMs-for-Video-Temporal-Grounding](#awesome-mllms-for-video-temporal-grounding-)
  - [1️⃣ 🧠 Functional Roles of MLLMs in VTG-MLLMs](#-functional-roles-of-mllms-in-vtg-mllms)
    - [Facilitator](#facilitator)
    - [Executor](#executor)
  - [2️⃣ 🛠️ Training Paradigms of VTG-MLLMs](#%EF%B8%8F-training-paradigms-of-vtg-mllms)
    - [Pretraining](#pretraining)
    - [Fine-Tuning](#fine-tuning)
    - [Training-Free](#training-free)
  - [3️⃣ 🎞️ Video Feature Processing in VTG-MLLMs](#%EF%B8%8F-video-feature-processing-in-vtg-mllms)
    - [Visual Feature](#visual-feature)
      - [Compression](#Compression)
      - [Refinement](#Refinement)
    - [Temporal Feature](#temporal-feature)
      - [Explicit](#Explicit)
      - [Implicit](#Implicit)
  - [4️⃣ 📊 Tasks and Benchmarks](#-tasks-and-benchmarks)
    - [Moment Retrieval](#moment-retrieval)
    - [Dense Captioning](#dense-captioning)
    - [Highlight Detection](#highlight-detection)
    - [Grounded VQA](#grounded-vqa)
  - [5️⃣ 📬 Contact](#contact)

---

## 🧠 Functional Roles of MLLMs in VTG-MLLMs

### Facilitator
MLLMs generate structured textual representations from video content to support downstream modules.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |

### Executor
MLLMs directly perform temporal boundary prediction via integrated multimodal reasoning.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |

---

## 🛠️ Training Paradigms of VTG-MLLMs

### Pretraining  
Pretraining in VTG-MLLMs aims to establish strong temporal reasoning capabilities through large-scale supervised learning.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |


### Fine-Tuning  
Adapts general-purpose MLLMs to downstream VTG tasks through supervised fine-tuning on temporally annotated training datasets.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |

### Training-Free  
Training-free approaches integrate pre-trained foundation models with specialized expert tools through the carefully designed pipeline architecture.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |

---

## 🎞️ Video Feature Processing in VTG-MLLMs

### Visual Feature

Efficient visual feature handling is essential for capturing more fine-grained temporal cues without overwhelming the model.

#### Compression  
Directly compress visual features from densely sampled frames within budget constraints.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |

#### Refinement  
Gradually refine predictions to maintain performance with the input token limitations.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |

### Temporal Feature

Precise temporal feature representation and modeling is crucial for aligning visual content with fine-grained timestamp intervals, enabling accurate temporal reasoning in VTG tasks.

#### Explicit  
Explicit modeling strategies directly furnish MLLMs with unambiguous temporal information, offering direct control and interpretability over temporal cues.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |

#### Implicit  
Implicit modeling leverages the inherent sequential processing and reasoning capabilities of LLMs or integrates temporal context more subtly during feature extraction.
| Title | Model | Date | Link | Venue |
| :---- | :---: | :--: | :--: | :---: |

---

## 📊 Tasks and Benchmarks

### Moment Retrieval  
Identify the temporal segment corresponding to a textual query.
| Title | Dataset | Date | Link | Venue |
| :---- | :-----: | :--: | :--: | :---: |

### Dense Captioning  
Generate multiple event descriptions with accurate temporal boundaries.
| Title | Dataset | Date | Link | Venue |
| :---- | :-----: | :--: | :--: | :---: 

### Highlight Detection  
Select keyframes that best match a given textual query.
| Title | Dataset | Date | Link | Venue |
| :---- | :-----: | :--: | :--: | :---: 

### Grounded VQA  
Answer time-sensitive questions based on video context, grounded in specific temporal evidence.
| Title | Dataset | Date | Link | Venue |
| :---- | :-----: | :--: | :--: | :---: 

---

## Contact
If you find our survey is useful in your research, please consider giving us a star 🌟 and cite the following paper:

```bibtex
@article{
}
```

If you have any question about this project, do not hesitate to contact me liuwei030224@gmail.com.