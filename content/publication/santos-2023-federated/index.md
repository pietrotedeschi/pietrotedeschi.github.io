---
title: Federated Learning for Reliable Model Updates in Network-Based Intrusion Detection

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Roger R dos Santos
- Eduardo K Viegas
- Altair O Santin
- Pietro Tedeschi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-10-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.228313Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Computers & Security*'
publication_short: ''

doi: '10.1016/j.cose.2023.103413'

abstract: 'Machine Learning techniques for network-based intrusion detection are widely adopted in the scientific literature. Besides being highly variable, network traffic behavior changes over time, demanding proposed schemes to be periodically updated to ensure their reliability. Unfortunately, their efficiency is significantly limited in production environments. This paper proposes a new Federated Learning model for reliable network-based intrusion detection with highly confident model updates over time. Our proposed scheme assesses the classification reliability in an unsupervised fashion and rejects potential misclassifications even when outdated. In addition, it significantly eases the model update cost by conducting it in a Federated Learning rationale. To evaluate the effectiveness of our solution, we conduct an experimental campaign with a new dataset, MAWIFlow, with over 7 TB of real network traffic spanning a year. The achieved results of our proposed model are striking. It respectively improves the average false-positive and false-negative rates by up to 12% and 9.6% when no model updates are conducted. If done so, it can further improve the false-positive rate by up to 13% while rejecting only 3.6% of events and demanding only 0.3% of events for model updates. Further, the comparison against the traditional Federated Learning approach confirms our model's remarkable performance in several scenarios. Finally, the quality and viability of our solution do prove that our approach can be successfully adopted for improving the accuracy and efficiency of classification systems in real-world scenarios where outdated models are prevalent and pave the way for future research in the area.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S0167404823003231'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
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
---
