
# SANDAR: Sanskrit Audio Numeric Dataset for Automatic Recognition

## Overview

**SANDAR** (Sanskrit Audio Numeric Dataset for Automatic Recognition) is a curated collection of **12,100 high-quality audio samples** of Sanskrit spoken digits (0 to 9). The dataset is developed to address the lack of publicly available Sanskrit speech resources and to support research in **Automatic Speech Recognition (ASR)**, **Multilingual Speech Systems**, and **Digital Sanskrit Applications**.

This corpus is especially suitable for:

- Building digit recognition models in Sanskrit  
- Benchmarking speech models on low-resource and ancient languages  
- Developing tools for digital Sanskrit learning, speech interfaces, and language preservation

---

## Motivation

While Sanskrit is one of the world's oldest languages and a cornerstone of Indian linguistic heritage, it remains underrepresented in modern ASR research. SANDAR fills this gap by offering:

- A clean, diverse, and structured dataset  
- Equal representation of male and female voices  
- Controlled recording conditions for high signal clarity  
- Open-access availability for academic and research use  

---

## Dataset Description

| Feature                | Details                                   |
|------------------------|-------------------------------------------|
| Total Samples          | 12,150                                    |
| Digits Covered         | 0 to 9                                    |
| Male Speakers          | 66 participants                           |
| Female Speakers        | 92 participants                           |
| Utterances per Digit   | Avg. 8 per digit per speaker              |
| Sampling Rate          | 16 kHz                                    |
| Bit Depth              | 16-bit PCM                                |
| Format                 | `.wav`                                    |

Each audio file is labeled with the corresponding Sanskrit digit and speaker metadata.

---

## File Structure

```
SANDAR/
├── README.md
├── Dataset
  ├── 0
    ├── 0_1_1.wav
  ├── 1
  ├── 2
  ├── 3
  ├── 4
  ├── 5
  ├── 6
  ├── 7
  ├── 8
  ├── 9
```
