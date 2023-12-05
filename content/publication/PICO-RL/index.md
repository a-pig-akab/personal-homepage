---
title: Payload-Independent Direct Cost Learning for Image Steganography

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Weixiang Li
- Shihang Wu
- Bin Li
- Weixuan Tang
- Xinpeng Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: 
  - ''
  - 'student first author'
  - ''

date: '2023-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-05T13:55:54.697834Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Circuits and Systems for Video Technology*'
publication_short: 'TCSVT'

doi: 10.1109/TCSVT.2023.3294291

abstract: Recent research has shown that architectures utilizing reinforcement learning (RL) are effective in cost-based image steganography. However, these architectures only learn embedding probabilities rather than costs, and are trained for a specific embedding payload, making it difficult to extend the trained model to serve other payloads. In this paper, we propose a payload-independent cost learning framework using RL called PICO-RL. This framework directly learns universal costs that can be applied to any payload. PICO-RL incorporates an optimal probability approximation (OPA) module that can calculate the required probability map for embedding simulation directly from a learned cost map for any payload, eliminating the need for time-consuming searches for a valid probability scaling parameter. Additionally, PICO-RL uses an advanced steganalysis environment network to provide more effective reward feedback for learning. During RL training, the learned cost maps of different payloads converge and eventually become similar under the OPA constraint, resulting in payload independence. Experimental results demonstrate that a well-trained PICO-RL model, which acts as a universal cost function, defines costs with superior security performance against steganalysis and has better coding compatibility when encoding with practical steganographic codes.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: ture

# Links
url_pdf: ''
url_code: 'https://github.com/a-pig-akab/PICO-RL_project.git'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/a-pig-akab/PICO-RL_project.git'
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10178049/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
