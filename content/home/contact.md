---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 160

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
  email: zhoumd@shanghaitech.edu.cn
  address:
    street: 393 Huaxia Middle Rd
    city: Pudong New Area
    region: Shanghai 
    postcode: '201210'
  coordinates:
    latitude: '31.178185434797314'
    longitude: '121.59482896327972'
  directions: 3-503, SIST Bldg

design:
  columns: '2'
---
