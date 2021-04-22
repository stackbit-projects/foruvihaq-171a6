---
title: އަޅުގަނޑުމެންނާ ގުޅުއްވާ
img_path: images/energetic-chestnut.png
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: name
    label: 'ނަން :'
    default_value: އަސްލުނަން ނުޖައްސަވާ
    is_required: true
  - input_type: email
    name: email
    label: އީމެއިލް
    default_value: ޕްރޮޓޮން މެއިލްފަދަ އެންކްރިޕްޓެޑް އީމެއެލް ބޭނުންކުރައްވާ
    is_required: true
  - input_type: select
    name: ކުރު ތަފްސީލް
    label: މައުޟޫޢު
    default_value: މައމިތަނުން ފާހަގަކޮށްލައްވާ
    options:
      - Error on the site
      - Sponsorship
      - Other
  - input_type: textarea
    name: message
    label: މެސްޖު ތިރީގައި ލިޔުއްވާ
    default_value: މެސެޖް މިތަނުގައި ހިއްސާކުރައްވާ!
  - input_type: checkbox
    name: consent
    label: >-
      މިފޯމުގައި ހިއްސާކުރެވިފައިވާ މަޢުލޫމާތުތަކުގައި އަމިއްލަ މީހާ އެނގޭނޭ
      ފަދަ މަޢުލޫމާތެއް ނުވެއެވެ
submit_label: Send Message
seo:
  title: Get in Touch
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Get in Touch
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'og:image'
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'twitter:image'
      value: images/contact.jpg
      relativeUrl: true
layout: contact
---
އަޅުގަނޑުމެންނާއި ގުޅުއްވުމަށް ތިރީގައިވާ ފޯމް ިފލް ކުރުމަށްފަހު ފޮނުވާލާ
