---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: wilsos66[at]mcmaster.ca
  address:
    street: 1200 Main Street W
    city: Hamilton
    region: Ontario
    postcode: L8N3Z5
    country: Canada
    country_code: Canada
  coordinates:
    latitude: '43.257998968'
    longitude: '-79.917996328'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

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
  columns: '1'
---

