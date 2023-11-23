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
      title: Financeurs
      user_groups:
          - funding
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: people
    id: partners
    content:
      title: Partenaires externes
      user_groups:
          - partners
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: people
    id: team
    content:
      title: Equipe
      user_groups:
          - Almanach
          - Multispeech
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: Contact
    id: contact
    content:
      title: Contact
      email: colaf@inria.fr


      
---