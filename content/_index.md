---
# Leave the homepage title empty to use the site title
title: Zerui Wang 
date: 2023-4-20
type: landing

sections:
  - block: v1/about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      title: About Me
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    id: publications
    content:
      title: Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        # exclude_featured: true
      count: 65536
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: news
    content:
      title: News
      text: |-
        - **2026:** [Jet-Long](/publication/jet-long/) has been accepted to NeurIPS 2026.
        - **Jul 2026:** Our [Jet-Long preprint](/publication/jet-long/) and [code](https://github.com/jet-ai-projects/Jet-Long) are available.
        - **May 2026:** I joined NVIDIA Research as a research intern.
        - **2026:** [FlexRL](/publication/flexrl/) appeared at ICLR 2026, and [Zeppelin](/publication/zeppelin/) appeared at EuroSys 2026.
  - block: markdown
    id: experience
    content:
      title: Experience
      text: |-
        ### Research Intern
        **[NVIDIA Research](https://www.nvidia.com/en-us/research/)** · May 2026 – Present

        ### Redstar Intern (Top Talent)
        **Xiaohongshu** · Started Oct 2025

        Working on LLM pretraining.
    design:
      columns: '2'
    # - block: portfolio
    # id: projects
    # content:
    #   title: Projects
    #   filters:
    #     folders:
    #       - project
    #   # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
    #   default_button_index: 0
    #   # Filter toolbar (optional).
    #   # Add or remove as many filters (`filter_button` instances) as you like.
    #   # To show all items, set `tag` to "*".
    #   # To filter by a specific tag, set `tag` to an existing tag name.
    #   # To remove the toolbar, delete the entire `filter_button` block.
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Deep Learning
    #       tag: Deep Learning
    #     - name: Other
    #       tag: Demo
    # design:
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '1'
    #   view: showcase
    #   # For Showcase view, flip alternate rows?
    #   flip_alt_rows: false
---
