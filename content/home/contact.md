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
      captcha: true 

  # Contact details (edit or remove options as required)
  email: danielworaeadu691@gmail.com
  phone: +233 59 550 7079
  address:
    street: Kenten
    city: Techiman
    region: Bono East
    postcode: '00233'
    country: Ghana
    country_code: GH
  coordinates:
    latitude: ''
    longitude: ''
  directions: 
  office_hours:
    - 'Monday 10:00 to 18:00'
    - 'Wednesday 09:00 to 18:00'
    - 'Friday 10:00 to 18:00'
  appointment_url: ''
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Wadman691'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://us04web.zoom.us/profile'

design:
  columns: '2'
---
