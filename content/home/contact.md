---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: txramsey@umich.edu
  phone: 734-223-4513
  address:
    street: 1863 Lake Lila Ln
    city: Ann Arbor
    region: MI
    postcode: '48105'
    country: United States
    country_code: US

  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/xun_tu'

design:
  columns: '2'
---
