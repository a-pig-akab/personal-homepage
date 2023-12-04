---
title: Payload-Independent Direct Cost Learning for Image Steganography

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Weixiang Li
- Shihang Wu
- Bin Li
- Weixuan Tang
- Xinpeng Zhang
author_notes:
- Equal contribution
- Equal contribution

date: '2023-01-01'
doi: 10.1109/TCSVT.2023.3294291

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-04T17:27:37.751492Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types:
- '2'

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Circuits and Systems for Video Technology*'
publication_short: In *ICW*

abstract: Recent research has shown that architectures utilizing reinforcement learning(RL) are effective in cost-based image steganography. However, these architectures
only learn embedding probabilities rather than costs, and are trained for a speciﬁc embedding payload, making it difﬁcult to extend the trained model to serve other payloads. In this paper, we propose a payload-independent cost learning framework using RL called PICO-RL. This framework directly learns universal costs that can be applied to any payload. PICO-RL incorporates an optimal probability approximation(OPA) module that can calculate the required probability map for embedding simulation directly from a learned cost map for any payload, eliminating the need for timeconsuming searches for a valid probability scaling parameter. Additionally, PICO-RL uses an advanced steganalysis environment network to provide more effective reward feedback for learning. During RL training, the learned cost maps of different payloads converge and eventually become similar under the OPA constraint, resulting in payload independence. Experimental results demonstrate that a well-trained PICO-RL model, which acts as a universal cost function, deﬁnes costs with superior security performance against steganalysis and has better coding compatibility when encoding with practical steganographic codes.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://ieeexplore.ieee.org/document/10178049/
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
url_dataset: https://github.com/wowchemy/wowchemy-hugo-themes
url_poster: ''
url_project: ''
url_slides: ''
url_source: https://github.com/wowchemy/wowchemy-hugo-themes
url_video: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
