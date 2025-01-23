---
title: 'A Pilot Study on Dialogue-Level Dependency Parsing for Chinese'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shuang Liu
  - Meishan Zhang
  - Min Zhang

# Author notes (optional)
author_notes:
  # - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
date: '2023-07-09'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'
publishDate: '2023-07-09'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['Conference paper']

# Publication name and optional abbreviated publication name.
publication: In *Findings of the Association for Computational Linguistics (ACL) 2023*
# publication_short: In *Findings of ACL 2023*

abstract: Dialogue-level dependency parsing has received insufficient attention, especially for Chinese. To this end, we draw on ideas from syntactic dependency and rhetorical structure theory (RST), developing a high-quality human-annotated corpus, which contains 850 dialogues and 199,803 dependencies. Considering that such tasks suffer from high annotation costs, we investigate zero-shot and few-shot scenarios. Based on an existing syntactic treebank, we adopt a signal-based method to transform seen syntactic dependencies into unseen ones between elementary discourse units (EDUs), where the signals are detected by masked language modeling. Besides, we apply single-view and multi-view data selection to access reliable pseudo-labeled instances. Experimental results show the effectiveness of these baselines. Moreover, we discuss several crucial points about our dataset and approach.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ['Dependency Parsing', 'Natural Language Processing', 'Zero-shot Learning', 'Few-shot Learning']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2023.findings-acl.607.pdf'
url_code: ''
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
