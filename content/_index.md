---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about
    id: about
    # Choose a user profile to display (a folder name within `content/authors/`)
    author: admin
    title: About Me
  - block: news-list
    id: news
    content:
      title: News
      folder: news
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications   
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '1'
      view: community/my_showcase
      flip_alt_rows: true
  - block: awards
    id: awards
    content:
      title: Awards
      folder: awards
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please fill in the following form to leave me a message.
      # Contact (add or remove contact options as necessary)
      email: chen[dot]zhao[at]kaust[dot]edu[dot]cn
      address:
        street: Office No. 3124, Building 13, KAUST
        city: Thuwal
        region: Makkah Province
        postcode: '23955-6900'
        country: Saudi Arabia
        country_code: KSA
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
