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
  email: mayuresh@umich.edu
  address:
    street: 1955 N. Fremont Ave.
    city: Idaho Falls
    region: ID
    postcode: '84301'
    country: United States
    country_code: US
  coordinates:
    latitude: '42.3207249'
    longitude: '-83.2362437'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me!
      link: 'https://twitter.com/mayuresh1016'
    - icon: linkedin
      icon_pack: fab
      name: Let's Connect!
      link: 'https://linkedin.com/in/mayuresh-savargaonkar'


design:
  columns: '2'
---
