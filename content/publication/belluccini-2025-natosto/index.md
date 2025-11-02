---
title: 'Privacy Preserving Underwater Collaborative Localization using Time Lock Puzzles'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- R. Praveen Jain
- Pietro Tedeschi
- Jeremy Nicola
- Abdelrahaman Aly
- Eduardo Soria-Vazquez
- Victor Sucasas

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-20'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.224560Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*IEEE INFOCOM 2024 - IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS)*'
publication_short: ''

doi: '10.1109/INFOCOMWKSHPS61880.2024.10620791'

abstract: 'This paper considers the issue of localizing a lost Autonomous Underwater Vehicle (AUV) using range and position measurements transmitted by an assisting AUV. Revealing the position of the assisting AUV could compromise its own safety and thus we need a privacy-preserving solution to this problem. Since this is a challenging task in the underwater domain, we propose to adopt Time Lock Puzzles, which keep the data of the assisting AUV encrypted until enough sequential work has been performed by the lost AUV. This ensures the safety of the assisting AUV, which gets enough time to move away from the revealed location. The generated delays are handled by augmenting the states of the lost AUV with the state of the lost AUV at the instant it receives a measurement. The augmented states are estimated with an Extended Kalman Filter. The efficacy of the proposed method is presented through a simulation campaign that shows how an AUV can be localized using delayed measurements by leveraging only single-range measurements.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10620791'
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