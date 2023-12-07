---
title: 'LiKe: Lightweight Certificateless Key Agreement for Secure IoT Communications'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pietro Tedeschi
- Savio Sciancalepore
- Areej Eliyan
- Roberto Di Pietro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-11-14'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.130306Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Internet of Things Journal*'
publication_short: ''

doi: '10.1109/JIOT.2019.2953549'

abstract: 'Certificateless public-key cryptography (CL-PKC) schemes are particularly robust against the leakage of secret information stored on a trusted third party (TTP). These security features are particularly relevant for Internet of Things (IoT) domains, where the devices are typically preconfigured with secret keys, usually stored locally on the TTP for following maintenance tasks. Despite some contributions already proposed for the adoption of CL-PKC schemes in constrained IoT devices, current solutions generally require high message overhead, are computationally demanding, and place a high toll on the energy budget. To close this gap, we propose LiKe, a lightweight pairing-free certificateless key agreement protocol suitable for integration in the latest ZigBee 3.0 protocol stack and constrained IoT devices. LiKe is an authenticated key agreement protocol characterized by: 1) ephemeral cryptographic materials; 2) support for intermittent connectivity with the TTP; 3) lightweight rekeying operations; and 4) robustness against impersonation attacks, even when information stored on the TTP is leaked. LiKe has been thoroughly described, and its security properties have been proved via formal tools. Moreover, we have implemented and tested it on real IoT devices, in networks with up to 11 nodes-the source code has been released as an open source. Results are striking: on the OpenMote-b hardware platform, LiKe requires a total time of 3.259 s to establish session keys on each participating device, and at most 0.258% of the overall battery capacity, emerging as a lightweight and energy-friendly solution. Finally, comparisons with competing solutions do show the superior quality and viability of our proposal.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://ieeexplore.ieee.org/document/8901222'
url_code: 'https://github.com/pietrotedeschi/like-iot'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.researchgate.net/profile/Pietro-Tedeschi/publication/337603563_LiKe_Presentationpdf/data/5ddfd252a6fdcc2837f3b99f/LiKe-Presentation.pdf'
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