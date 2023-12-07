---
title: SecureAIS-Securing Pairwise Vessels Communications

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Ahmed Aziz
- Pietro Tedeschi
- Savio Sciancalepore
- Roberto Di Pietro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-06-29'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.141113Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*IEEE Conference on Communications and Network Security (CNS)*'
publication_short: ''

doi: '10.1109/CNS48642.2020.9162320'

abstract: 'Modern vessels increasingly rely on the Automatic Identification System (AIS) digital technology to wirelessly broadcast identification and position information to neighboring vessels and ports. AIS is a time-slotted protocol that also provides unicast messages-usually employed to manage self-separation and to exchange safety information. However, AIS does not provide any security feature. The messages are exchanged in clear-text, and they are not authenticated, being vulnerable to several attacks, including forging and replay. Despite the existing contributions in the literature propose some strategies to overcome the exposed weaknesses, some are insecure, others do not comply with the standard, while the remaining few ones would introduce an unacceptable overhead-that is, they would require a relevant number of AIS-time slots, because of the limited payload available for each time-slot. In this paper, we propose SecureAIS, a key agreement scheme that allows any pair of vessels in reach of an AIS radio to agree on a shared session key of the desired length, by requiring just a fraction of the AIS time-slots of competing solutions. Further, the scheme is fully standard compliant and does not require any modification to the available hardware. The proposed scheme integrates the Elliptic Curve Qu-Vanstone (ECQV) implicit certification scheme and the Elliptic Curve Diffie Hellman (ECDH) key agreement technique, requiring moderate computational overhead while enjoying an optimal usage of the available bandwidth. When configured with the highest security level of 256 bits, SecureAIS allows two AIS transceivers to agree on a shared session key in 20 time-slots, against the 96 time-slots required by the competing solution based on traditional X.509 certificates. The proposed solution has been implemented and tested in a real scenario, while its security has been formally evaluated through the ProVerif tool. Finally, the source code of our Proof-of-concept using GNURadio and Ettus Research X310 has been also released as open-source to pave the way to further research by both Industry and Academia in maritime communication security.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9162320'
url_code: 'https://github.com/pietrotedeschi/secureais'
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
