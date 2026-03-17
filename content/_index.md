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
        - 🎉 Our new paper has been accepted by ICLR 2026.
  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Redstar Intern (Top Talent)
          company: Xiaohongshu
          date_start: '2026-03-01'
          date_end: ''
          description: |2-
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
