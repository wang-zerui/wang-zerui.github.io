---
title: 'Characterization of Large Language Model Development in the Datacenter'

authors:
    - Qinghao Hu*
    - Zhisheng Ye*
    - admin*
    - Guoteng Wang
    - Meng Zhang
    - Qiaoling Chen
    - Peng Sun
    - Dahua Lin
    - Xiaolin Wang
    - Yingwei Luo
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: "2024-04-01T00:00:00Z"
# doi: '10.48550/arXiv.2302.11665'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *21st USENIX Symposium on Networked Systems Design and Implementation (NSDI '24) * (CCF-A)
publication_short: In *NSDI 2024*

abstract: 'Large Language Models (LLMs) have presented impressive performance across several transformative tasks. However, it is non-trivial to efficiently utilize large-scale cluster resources to develop LLMs, often riddled with numerous challenges such as frequent hardware failures, intricate parallelization strategies, and imbalanced resource utilization. In this paper, we present an in-depth characterization study of a six-month LLM development workload trace collected from our GPU datacenter Acme. Specifically, we investigate discrepancies between LLMs and prior task-specific Deep Learning (DL) workloads, explore resource utilization patterns, and identify the impact of various job failures. Our analysis summarizes hurdles we encountered and uncovers potential opportunities to optimize systems tailored for LLMs. Furthermore, we introduce our system efforts: (1) fault-tolerant pretraining, which enhances fault tolerance through LLM-involved failure diagnosis and automatic recovery. (2) decoupled scheduling for evaluation, which achieves timely performance feedback via trial decomposition and scheduling optimization.'

# Summary. An optional shortened abstract.
# tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://www.usenix.org/system/files/nsdi24-hu.pdf'
url_code: 'https://github.com/InternLM/AcmeTraces'
url_dataset: 'https://github.com/InternLM/AcmeTrace'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---