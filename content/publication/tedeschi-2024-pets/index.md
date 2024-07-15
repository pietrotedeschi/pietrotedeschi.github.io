---
title: 'Selective Authenticated Pilot Location Disclosure for Remote ID-enabled Drones'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pietro Tedeschi
- Siva Ganesh Ganti
- Savio Sciancalepore

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.224560Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Proceedings on Privacy Enhancing Technologies 2024*'
publication_short: ''

doi: '10.56553/popets-2024-0091'

abstract: 'Remote Identification (RID) regulations recently promulgated worldwide are forcing commercial drones to broadcast wirelessly the location of the pilot in plaintext. However, in many real-world use cases, the plaintext availability of such information leads to privacy issues, allowing the extraction of sensitive information about the pilot and confidential details about the drone&rsquo;s business. To address this issue, this paper proposes SNELL, a RID-compliant solution for selective authenticated pilot location disclosure. Using SNELL, a drone can disclose RID messages providing encrypted information about the pilot&rsquo;s location. At the same time, thanks to the smart integration of Ciphertext-Policy Attribute-Based Encryption (CP-ABE) techniques, the data about the pilot location can be decrypted only by receivers with a set of attributes satisfying an access control policy chosen by the drone at run-time. Thanks to an extensive experimental assessment carried out on a real medium-end drone (Lumenier QAV-R) and a constrained chip (ESP32), we demonstrate that SNELL can fulfil all the requirements imposed by RID and relevant standardization authorities in terms of pilot location update time and message size while also requiring negligible energy toll on RID-compliant drones.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: true

# Links
url_pdf: 'https://petsymposium.org/popets/2024/popets-2024-0091.pdf'
url_code: 'https://github.com/pietrotedeschi/snell'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://petsymposium.org/popets/2024/popets-2024-0091.php'
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: 'Selective Authenticated Pilot Location Disclosure for Remote ID-enabled Drones'
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---