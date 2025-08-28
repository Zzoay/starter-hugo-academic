---
title: 'Chart-CoCa: Self-Improving Chart Understanding of Vision LMs via Code-Driven Synthesis and Candidate-Conditioned Answering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Qiong Luo

# Author notes (optional)
author_notes:
  # - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
date: '2025-08-16'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'
publishDate: '2025-08-16'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['Conference paper']

# Publication name and optional abbreviated publication name.
publication: In *The 34th ACM International Coference on Information and Knowledge Managemet (CIKM) 2025*
# publication_short: In *Findings of ACL 2023*

abstract: Vision Language Models (VLMs) often struggle with chart understanding tasks, particularly in accurate chart description and complex reasoning. Synthetic data generation is a promising solution, while usually facing the challenge of noise labels. To address this challenge, we first introduce a chart synthesis pipeline that generates aligned chart-question-answer triplets through code generation and execution, ensuring the reliability of synthetic data without human intervention. Furthermore, inspired by test-time scaling that increases inference budget and thereby improves performance, we design a candidate-conditioned answering process. The VLM first generates multiple responses per query, and then synthesizes the final answer by contextualizing these candidates. Experiments demonstrate significant improvements, with up to 15.50 points accuracy gain over the initial VLM, in a fully self-improving paradigm without either human-labeled data or external models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ['Question Answering', 'Chart Understanding', 'Multimodal Large Language Models', 'Data Synthesis']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2508.11975'
url_code: 'https://github.com/Zzoay/Chart-CoCa'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
