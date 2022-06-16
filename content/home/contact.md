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
  email: edsonjohn3@gmail.com
  phone: + 52 1 449 459 02 45
  address:
    street: 450 Hacienda Texmelucan
    city: Mexico City
    region: CDMX
    postcode: '04960'
    country: Mexico
    country_code: MX
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building 1 and turn left to Office 2
  office_hours:
    - 'Monday 8:00 to 13:00'
    - 'Wednesday 8:00 to 13:00'
    - 'Friday  8:00 to 13:00'
  appointment_url: 'https://calendly.com'
  contact_links:
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
