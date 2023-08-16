---
date: "2022-10-24"

# Sections
sections:

# Hero
- block: hero
  content:
    text: "Working on data integration to discover new drugs and diagnostics for human
      pathogens. \n<!--GitHub Button JS-->\n<script async defer src=\"https://buttons.github.io/buttons.js\"></script>"
    title: The Trypanosomatics Laboratory
  design:
    background:
      filters:
        brightness: 1
      image:
        filename: bubbles-wide-tryp-binary.jpg
      size: cover
      text_color_light: true

# Biography
- block: about.biography
  content:
    title: About
    username: trypanosomatics
  id: about

# Slider 
- block: slider
  content:
    slides:
    - align: left
      background:
        color: null
        fit: cover
        image:
          filename: tdrtargets-logo-v6-260x260.jpg
          filters:
            brightness: 0.5
        position: center
      content: 'Chemogenomics database: drug discovery for neglected diseases'
      link:
        icon: book-open
        icon_pack: fas
        text: Search/Browse
        url: https://tdrtargets.org
      title: TDR Targets 6
    - align: center
      background:
        image:
          filename: aprank-v1.png
          filters:
            brightness: 0.5
        position: center
      content: A tool for genome-wide antigenicity predictions
      fit: cover
      link:
        icon: open-access
        icon_pack: ai
        text: Publication
        url: publication/2021-ricci-aprank-frontiers
      title: APRANK
    - align: right
      background:
        color: null
        fit: contain
        image:
          filename: chagastope.png
          filters:
            brightness: 0.7
        position: right
      content: An Atlas of Chagas Disease Antigens and Epitopes
      link:
        icon: map
        icon_pack: fas
        text: Visit
        url: https://chagastope.org
      title: Chagastope
  design:
    interval: false
    is_fullscreen: false
    loop: false
    slide_height: 400px
  id: slider

# People
- block: people
  content:
    subtitle: The people behind the tryps and bits
    title: This is Us
    user_groups:
    - Investigators
    - Grad Students
    - Alumni
    - Past Lab Members
    - Collaborators
    - Visitors
    - Administration
  design:
    show_interests: true
    show_social: true
  id: people

# 
- block: features
  content:
    items:
    - description: 90%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 100%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 10%
      icon: camera-retro
      icon_pack: fas
      name: Photography
    title: Skills

# 
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: GenCoin
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2021-01-01"
      description: |2-
          Responsibilities include:

          * Analysing
          * Modelling
          * Deploying
      location: California
      title: CEO
    - company: University X
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Professor of Semiconductor Physics
    title: Experience
  design:
    columns: "2"

# Accomplishments
#- block: accomplishments
#  content:
#    date_format: Jan 2006
#    items:
#    - certificate_url: https://www.coursera.org
#      date_end: ""
#      date_start: "2021-01-25"
#      description: ""
#      organization: Coursera
#      organization_url: https://www.coursera.org
#      title: Neural Networks and Deep Learning
#      url: ""
#    - certificate_url: https://www.edx.org
#      date_end: ""
#      date_start: "2021-01-01"
#      description: Formulated informed blockchain models, hypotheses, and use cases.
#      organization: edX
#      organization_url: https://www.edx.org
#      title: Blockchain Fundamentals
#      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#    - certificate_url: https://www.datacamp.com
#      date_end: "2020-12-21"
#      date_start: "2020-07-01"
#      description: ""
#      organization: DataCamp
#      organization_url: https://www.datacamp.com
#      title: Object-Oriented Programming in R
#      url: ""
#    subtitle: null
#    title: Accomplish&shy;ments
#  design:
#    columns: "2"


- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: News and Announcements
    text: Bits and Pieces
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts

# Projects portfolio 
- block: portfolio
  id: projects
  content:
    title: Projects
    subtitle: my subtitle
    buttons:
    - name: All
      tag: '*'
    - name: Immunomics
      tag: Immunomics
    - name: Drug Discovery
      tag: chemogenomics
    - name: COVID-19
      tag: covid
    - name: Genetic diversity
      tag: genetic-diversity
    default_button_index: 0
    filters:
      folders:
      - project    
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  

# Gallery 
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="lab" resize_options="300x300">}}'
    title: Gallery
  design:
    columns: "1"

# Featured publications
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured

# Recent publications
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation

# Talks | Presentations
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Presentations
  design:
    columns: "2"
    view: compact
  id: talks

# Tag cloud | Popular topics
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"

# Contact Us 
- block: contact
  content:
    title: Contact
    id: contact
    address:
      city: San Martín
      country: Argentina
      country_code: AR
      postcode: "B1650HMQ"
      region: Buenos Aires
      street: 25 de Mayo 1401
    coordinates: 
      latitude: '-34.579239'
      longitude: '-58.525103'
    appointment_url: https://calendly.com/trypanosomatics
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/trypanosomatics
      name: DM Us
    directions: Edificio IIB (Biotecnología), 1st Floor
    email: info@trypanosomatics.org
    #form:
    #  formspree:
    #    id: null
    #  netlify:
    #    captcha: false
    #  provider: netlify
    office_hours:
    - Monday &ndash; Friday 09:00 to 19:00 [ART](https://www.timeanddate.com/worldclock/argentina/buenos-aires)
    phone: +54 11 4006-1500 exts 2110, 2120, 2107
    subtitle: null
    text: Reach out, write, 
  design:
    columns: "2"
title: null
type: landing
---
