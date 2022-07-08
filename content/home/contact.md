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
  email: Lallen@umn.edu
  address:
    street: 56 East River Road
    city: Minneapolis
    region: MN
    postcode: '55455'
    country: United States
    country_code: US
  directions: 250 Education Sciences Building


design:
  columns: '2'
---
