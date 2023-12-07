---
title: 'ARID: Anonymous Remote IDentification of Unmanned Aerial Vehicles'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pietro Tedeschi
- Savio Sciancalepore
- Roberto Di Pietro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-12-06'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.182364Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Annual Computer Security Applications Conference (ACSAC) 2021*'
publication_short: ''

doi: '10.1145/3485832.3485834'

abstract: 'To enable enhanced accountability of Unmanned Aerial Vehicles (UAVs) operations, the US-based Federal Avionics Administration (FAA) recently published a new dedicated regulation, namely RemoteID, requiring UAV operators to broadcast messages reporting their identity and location. The enforcement of such a rule, mandatory by 2022, generated significant concerns on UAV operators, primarily because of privacy issues derived by the indiscriminate broadcast of the plain-text identity of the UAV on the wireless channel. In this paper, we propose ARID, a solution enabling RemoteID-compliant Anonymous Remote Identification of UAVs. The adoption of ARID allows UAVs to broadcast RemoteID-compliant messages using ephemeral pseudonyms that only a Trusted Authority, such as the FAA, can link to the long-term identifier of the UAV and its operator. Moreover, ARID also enforces UAV message authenticity, to protect UAVs against impersonation and spoofed reporting, while requiring an overall minimal toll on the battery budget. Furthermore, ARID generates negligible overhead on the Trusted Authority, not requiring the secure maintenance of any private database. While the security properties of ARID are thoroughly discussed and formally verified with ProVerif, we also implemented a prototype of ARID on a real UAV, i.e., the 3DR-Solo drone, integrating our solution within the popular Poky Operating System, on top of the widespread MAVLink protocol. Our experimental performance evaluation shows that the most demanding configuration of ARID takes only ≈ 11.23 ms to generate a message and requires a mere 4.72 mJ of energy. Finally, we also released the source code of ARID to foster further investigations and development by Academia, Industry, and practitioners.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3485832.3485834'
url_code: 'https://github.com/pietrotedeschi/arid'
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