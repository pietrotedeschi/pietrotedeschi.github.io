---
title: Mitigating Energy Depletion Attacks in IoT via Random Time-Slotted Channel Access

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Savio Sciancalepore
- Pietro Tedeschi
- Usman Riasat
- Roberto Di Pietro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-10-04'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.174662Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2021 IEEE Conference on Communications and Network Security*'
publication_short: ''

doi: '10.1109/CNS53000.2021.9705038'

abstract: 'Energy depletion attacks represent a challenging threat towards the secure and reliable deployment of low-power Internet of Things (IoT) networks. Indeed, by simply transmitting canning standard-compliant packets to a target IoT device, an adversary can quickly exhaust target devices available energy and reduce network lifetime, leading to extensive Denial-of-Service (DoS). Current solutions to tackle energy depletion attacks mainly rely on ex-post detection of the attack and the adoption of follow-up countermeasures. Still, the cited approaches cannot prevent external adversaries from sending wireless packets to target devices and draining down their energy budget. In this paper, we present RTSCA, a novel countermeasure to energy depletion attacks in IoT networks, that leverages Random Time-Slotted Channel Access. RTSCA randomizes channel access operations executed by a couple of directly-connected IoT devices operating through the IEEE 802.15.4 MAC, significantly reducing the time window of opportunity for the attacker, with little-to-none energy cost on legitimate IoT devices. RTSCA also includes a detection mechanism targeted to the recently-introduced Truncate-after-Preamble (TaP) energy depletion attacks, that leverages the observation of error patterns in the received packets. We carried out an extensive performance assessment campaign on real Openmote-b IoT nodes, showing that RTSCA forces the adversary to behave as a (sub-optimal) reactive jammer to achieve energy depletion attacks. In such a setting, the adversary has to spend between 42.5% and 55% more energy to carry out the attack, while at the same time having no deterministic chances of success.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9705038'
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
