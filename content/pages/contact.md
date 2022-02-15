---
title: Contact
sections:
  - type: form_section
    content: |-
      ## Ask A Question
      Thank you for your interest in the Doctrine of Discovery Project.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Question
        default_value: Your question
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Submit
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image: images/pattern.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
seo:
  title: Contact
  description: This is the about page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: About
      keyName: property
    - name: 'og:description'
      value: This is the about page
      keyName: property
    - name: 'og:image'
      value: images/about.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: About
    - name: 'twitter:description'
      value: This is the about page
    - name: 'twitter:image'
      value: images/about.png
      relativeUrl: true
layout: advanced
---
Thank you for your interest in the Doctrine of Discovery Project you can contact us at info@doctrineofdiscovery.org
