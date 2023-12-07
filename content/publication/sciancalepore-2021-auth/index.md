---
title: 'Auth-AIS: Secure, Flexible, and Backward-Compatible Authentication of Vessels AIS Broadcasts'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Savio Sciancalepore
- Pietro Tedeschi
- Ahmed Aziz
- Roberto Di Pietro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-03-30'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.167009Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Dependable and Secure Computing*'
publication_short: ''

doi: '10.1109/TDSC.2021.3069428'

abstract: 'Automatic Identification System (AIS) is the de-facto communication standard used by vessels to broadcast identification and position information. However, being AIS communications neither encrypted nor authenticated, they can be eavesdropped and spoofed by adversaries, leading to potentially threatening scenarios. Existing solutions, including the ones conceived in the avionics domain, do not consider integration with the AIS standard, and they do not provide protection against rogue messages flooding. In this article, we propose Auth-AIS, a secure, flexible, standard-compliant, and backward-compatible authentication framework to secure AIS broadcast messages. Auth-AIS leverages existing sound cryptographic tools, including TESLA and Bloom Filters, inheriting their security properties while contextualizing them in the AIS technology. Auth-AIS is a software-only solution, that can be seamlessly integrated into existing AIS deployments, without requiring any hardware replacement. Its innovative design also provides backward-compatibility—i.e., Auth-AIS messages can be received also by AIS users not adopting Auth-AIS, while renouncing at its security guarantees. Auth-AIS can work in either two configuration modes: Deterministic Security Configuration, able to achieve low-delay authentication with a message overhead of 75 percent, or Probabilistic Security Configuration, reducing the message overhead down to 35.71 percent, while experiencing a marginal increase in the authentication delay. All these security configurations guarantee an 80 bits equivalent security level and false-positive rate less than 2 --40 . Note that these latter security parameters can easily be tuned to fit different security requirements. Finally, the source code of Auth-AIS in the GNURadio ecosystem has been released as open-source, to foster research activities from both Industry and Academia on secure AIS communications.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9390297'
url_code: 'https://github.com/pietrotedeschi/Auth-AIS'
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
