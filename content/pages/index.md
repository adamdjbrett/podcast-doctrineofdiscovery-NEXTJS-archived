---
title: Home
sections:
  - type: hero_section
    title: Welcome to Mapping the Doctrine of Discovery Podcast
    subtitle: >-
      Presented by the Indigenous Values Initiative, American Indian Law
      Alliance.
    content: |
      Helping listeners contextualize the Doctrine of Discovery.
    actions:
      - label: Subscribe to Podcast
        url: /subscribe
        style: primary
    image: /images/mapping-doctrine-of-discovery-favicon.png
    image_alt: >-
      The Mapping the Doctrine of Discovery logo is a compass rose covered in
      blood.
    media_position: left
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/hero-background.jpg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 20
    has_border: true
  - type: blog_feed_section
    title: Latest Episodes
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 6
    show_image: true
    show_date: true
    show_categories: false
    show_author: false
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: none
    background_image: images/pattern.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
  - type: grid_section
    title: Subscribe
    grid_items:
      - title: Apple Podcasts
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: https://podcasts.apple.com/us/podcast/mapping-the-doctrine-of-discovery/id1609802758
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-1.svg
        image_alt: Apple Podcasts icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Spotify
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: https://open.spotify.com/show/5VoYjujmNFCYS89vSsgl1c
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-2.svg
        image_alt: Spotify icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: PocketCast
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: https://pca.st/ah3neigt
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/pocketcasts.svg
        image_alt: PocketCast icon
        image_position: top
        image_align: center
        image_has_padding: true
    grid_cols: three
    grid_gap_horiz: medium
    grid_gap_vert: medium
    enable_cards: false
    align: center
    padding_top: large
    padding_bottom: large
    has_border: true
    background_color: secondary
    background_image: images/subscribe-background.jpg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 10
  - type: grid_section
    title: Partners
    subtitle: >-
      This project was supported by grants from the Syracuse University Engaged
      Humanities Network and the Henry Luce Foundation.
    align: center
    grid_items:
      - image: /images/indigenousvalues-2020.png
        image_align: center
        image_alt: Indigenous Values Initiative Logo
      - image: /images/aila-square-sm.png
        image_alt: American Indian Law Alliance
        image_align: center
      - image: /images/SYRACUSE_Horizontal_1Line_KNOCKOUT_white.png
        image_alt: Syracuse University logo
        image_align: center
      - image: /images/LUCE-Logo-Full-Mono-white-L.png
        image_alt: Henry Luce Foundation
        image_align: center
      - image_alt: Gatsby logo
        image_align: center
      - image_alt: Twilio logo
        image_align: center
      - image_alt: Contentful logo
        image_align: center
      - image_alt: Forestry logo
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
    has_border: true
    background_color: none
  - type: form_section
    content: |
      ## Subscribe

      Stay current and learn more by joining our email list.
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
  title: Mapping the Doctrine of Discovery Podcast
  description: >-
    Mapping the Doctrine of Discovery Podcast. Contextualizing the Doctrine of
    Christian Discovery and Domination and its influence on US law.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Mapping the Doctrine of Discovery Podcast
      keyName: property
    - name: 'og:description'
      value: >-
        Mapping the Doctrine of Discovery Podcast. Contextualizing the Doctrine
        of Christian Discovery and Domination and its influence on US law.
      keyName: property
    - name: 'og:image'
      value: /images/onondaga-lake-east-shoreline.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Mapping the Doctrine of Discovery
    - name: 'twitter:description'
      value: >-
        Mapping the Doctrine of Discovery Podcast. Contextualizing the Doctrine
        of Christian Discovery and Domination and its influence on US law.
    - name: 'twitter:image'
      value: /images/onondaga-lake-east-shoreline.jpg
      relativeUrl: true
layout: advanced
---
