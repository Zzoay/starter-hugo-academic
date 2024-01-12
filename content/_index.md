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
        company: CoAI Lab at Tsinghua University
        # company_url: https://coai.cs.tsinghua.edu.cn/
        # company_logo: org-x
        location: Beijing
        date_start: '2023-05-29'
        date_end: '2023-12-31'
        description: |2-
          * Research on natural language processing (especially AI for good)
          * Research on conversational system (especially on emotion support, empathetic and human-like systems)
      - title: Algorithm Intern
        company: Lingxin Intelligence
        location: Beijing
        date_start: '2023-05-29'
        date_end: '2023-12-31'
        description: |2-
          * Algorithmic engineering on LLM-based character conversational system
          * Algorithmic engineering on LLM-based document reader
      - title: Engineering Intern
        company: Guangdong Provincial Meteorological Bureau
        location: Guangzhou
        date_start: '2019-04-28'
        date_end: '2019-08-31'
        description: |2-
          * Development of a platform for meteorological data collection and analysis
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2023-12-01'
          description: ''
          organization: The Ministry of Education of China
          organization_url: ''
          title: National Scholarship
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-09-01'
          description: ''
          organization: Tianjin University
          organization_url: ''
          title: Extraordinary Academic Scholarship of TJU
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-06-01'
          description: ''
          organization: Guangdong University of Technology
          organization_url: ''
          title: Outstanding Graduate of GDUT
          url: ''
    design:
      columns: '2'
---
