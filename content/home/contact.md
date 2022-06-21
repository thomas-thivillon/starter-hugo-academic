---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
# Email form provider
#form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: thomas.thivillon[at]dauphine.eu
# phone: 888 888 88 88
  address:
    street: DIAL - Université Paris Dauphine - PSL, 4 rue d'Enghien
    city: Paris
#region: CA
    postcode: '75010'
    country: France
#country_code: US
  coordinates:
    latitude: 
    longitude: 
  directions: 
#office_hours:
#appointment_url:
#contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
