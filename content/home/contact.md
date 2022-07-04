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
  autolink: false

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: jing.chen@ntu.edu.sg
  address:
    street: 50 Nanyang Avenue
    city: Singapore
    postcode: 639798
    country: Singapore
  contact_links:

design:
  columns: '2'
---
