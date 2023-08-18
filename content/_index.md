---
date: "2023-07-23"
sections:

- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - description: #100%
      icon: r-project
      icon_pack: fab
      name: R
    - description: #100%
      icon: earth-americas
      icon_pack: fas
      name: Ecological Niche Modeling
    - description: #90%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    title: Skills

- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: list
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      featured_only: false
      folders:
      - publication-in-review
    title: Publications Under Review
  design:
    columns: "2"
    view: citation
  id: review
  
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: diversity
      tag: diversity
    - name: evolutionary
      tag: evolutionary
    - name: null models
      tag: null models
    default_button_index: 0
    filters:
      folders:
      - software
    title: Software
  design:
    columns: "1"
    flip_alt_rows: false
    view: compact
  id: software
  
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Atlantic Forest
      tag: Atlantic Forest
    - name: Cerrado
      tag: Cerrado
    - name: birds
      tag: birds
    - name: anura
      tag: anura
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects

- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
    
- block: contact
  content:
    address:
      city: Ilhéus
      country: Brazil
      country_code: BR
      postcode: "45662-000"
      region: BA
      street: Laboratório de Ecologia Aplicada à Conservação – LEAC, Rodovia Jorge Amado, km 16, Salobrinho
    contact_links:
    - icon: whatsapp
      icon_pack: fab
      link: https://wa.me/5573999064967
      name: Whatsapp Me
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/NeanderHeming
      name: DM Me
    - icon: skype
      icon_pack: fab
      link: skype:neandermh
      name: Skype Me
    directions: <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5433.517806327294!2d-39.17625874594489!3d-14.797990490681052!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x739a98cfd6e7d3d%3A0x1ccd602c903dc6c8!2sLaborat%C3%B3rio%20de%20Ecologia%20Aplicada%20%C3%A0%20Conserva%C3%A7%C3%A3o%20-%20Applied%20Ecology%20%26%20Conservation%20Lab!5e1!3m2!1sen!2sbr!4v1692187568467!5m2!1sen!2sbr" width="500" height="375" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    email: neanderh@yahoo.com.br
    office_hours:
    phone: 
    subtitle: null
    text: 
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
