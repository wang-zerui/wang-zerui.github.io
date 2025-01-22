---
title: 'SchedMate: Large Language Models are DL Scheduling Enhancers'

authors:
    - admin
    - Qinghao Hu
    - Ana Klimovic
    - Xingcheng Zhang
    - Peng Sun
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: "2024-04-01T00:00:00Z"
# doi: '10.48550/arXiv.2302.11665'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: In *21st USENIX Symposium on Networked Systems Design and Implementation (NSDI '24 Poster Session) * 
publication_short: In *NSDI 2024 Poster*

abstract: 'Existing deep learning cluster schedulers make their scheduling decisions on partial job information, such as resource utilization metrics obtained through profiling. Incorporating a broader range of information dimensions could enable these schedulers to make more optimal decisions. Recent advancements in Large Language Models (LLMs) present a promising avenue for efficiently extracting valuable insights from original code base and execution logs, potentially enhancing scheduling efficacy. In this work, we propose SchedMate, designed to enhance the performance of deep learning schedulers by incorporating LLMs and several advanced techniques. It employs an LLM-based agent to meticulously analyze user files within the working directory, extracting comprehensive metadata based on scheduling parameters. SchedMate utilizes a version management module to store and track the historical jobs metadata and their fine-grained changes, enabling fast extraction of metadata for repeated jobs and lower token consumption.  We plan to integrate SchedMate into multiple novel DL schedulers to further improve their performance.'

# Summary. An optional shortened abstract.
# tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'schedmate.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---