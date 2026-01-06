---
title: 'TRAMBA: A Hybrid Transformer and Mamba Architecture for Practical Audio and Bone Conduction Speech Super Resolution and Enhancement on Mobile and Wearable Platforms'

authors:
  - admin
  - Yueyuan Sui
  - Junxi Xia
  - Xiaofan Jiang
  - Stephen Xia

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-11-01T00:00:00Z'
doi: '10.1145/3699757'

publishDate: '2024-11-01T00:00:00Z'

publication_types: ['2']

publication: In *Proceedings of the ACM on Interactive, Mobile, Wearable, and Ubiquitous Technologies*
publication_short: In *IMWUT / UbiComp'25*

abstract: We propose TRAMBA, a hybrid transformer and Mamba architecture for acoustic and bone conduction speech enhancement, suitable for mobile and wearable platforms. Bone conduction speech enhancement has been impractical to adopt in mobile and wearable platforms for several reasons - (i) data collection is labor-intensive, resulting in scarcity; (ii) there exists a performance gap between state-of-art models with memory footprints of hundreds of MBs and methods better suited for resource-constrained systems. To adapt TRAMBA to vibration-based sensing modalities, we pre-train TRAMBA with audio speech datasets that are widely available. Then, users fine-tune with a small amount of bone conduction data. TRAMBA outperforms state-of-art GANs by up to 7.3% in Perceptual Evaluation of Speech Quality (PESQ) and 1.8% in Short-Time Objective Intelligibility (STOI), with an order of magnitude smaller memory footprint and an inference speed up of up to 465 times. We integrate TRAMBA into real systems and show that TRAMBA (i) improves battery life of wearables by up to 160% by requiring less data sampling and transmission; (ii) generates higher quality voice in noisy environments than over-the-air speech; (iii) requires a memory footprint of less than 20.0 MB.

summary: A hybrid transformer-Mamba architecture for wearable speech enhancement using bone conduction sensors, achieving superior quality with 160% battery life improvement and 465x faster inference.

tags: []

featured: true

url_pdf: 'tramba.pdf'
url_code: 'https://github.com/IMEC-Northwestern/TRAMBA'
url_dataset: 'https://github.com/IMEC-Northwestern/TRAMBA/tree/main/data'
url_poster: ''
url_project: 'https://imec-northwestern.github.io/TRAMBAPage/'
url_slides: 'tramba_ubicomp25.pdf'
url_source: ''
url_video: ''

image:
  focal_point: ''
  preview_only: false

projects: []

slides: ""
---
