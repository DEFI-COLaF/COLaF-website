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
      # Choose a user profile to display (a folder name within `content/authors/`)
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
      title: Partenaires
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
          - almanach
          - multispeech
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: markdown
    id: contact
    content:
      title: Contact
      # Choose a user profile to display (a folder name within `content/authors/`)
---