---
# Leave the homepage title empty to use the site title
title: 'COLaF'
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: COLaF
      username: admin
  - block: people
    id: funding
    content:
      title: Core Team
      user_groups:
          - funding
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: people
    id: partners
    content:
      title: Partners laboratories and institutions
      user_groups:
          - partners
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: people
    id: team
    content:
      title: The Team
      user_groups:
          - ALMAnaCH
          - Multispeech
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: collection
    id: results
    content:
      title: Results
      filters:
        folders:
          - result
    design:
      view: 2
      columns: 1
  - block: collection
    id: publications
    content: 
      title: Publications
      filters:
        folders:
          - publications
    design:
      view: 2
      columns: 1
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        To contact us: colaf@inria.fr<br/>
        To subscribe to our mailing list: [here](https://sympa.inria.fr/sympa/info/colaf-communaute)
    design:
      columns: 1

---
