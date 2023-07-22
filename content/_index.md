---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
      - title: Research Intern
        company: THU-CoAI
        # company_url: https://coai.cs.tsinghua.edu.cn/
        # company_logo: org-x
        location: Beijing
        date_start: '2023-05-29'
        date_end: ''
        description: |2-
          * Research on natural language processing
          * Research on conversational system
      - title: Algorithm Intern
        company: Lingxin Intelligence
        location: Beijing
        date_start: '2023-05-29'
        date_end: ''
        description: |2-
          * Algorithmic engineering on conversational system
      - title: Engineering Intern
        company: Guangdong Provincial Meteorological Bureau
        location: Guangzhou
        date_start: '2019-04-28'
        date_end: '2019-08-31'
        description: |2-
          * Development of a platform for meteorological data collection and analysis
    design:
      columns: '2'
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
---
