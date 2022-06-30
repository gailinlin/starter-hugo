---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: 联系方式
subtitle:

content:
  # Contact (edit or remove options as required)

  邮箱: test@example.org
  电话: 888 888 88 88
  地址:
    street: No. 1539, Haigang Avenue
    city: Shanghai
    region: Pudong District
    postcode: '201306'
    country: China
    country_code: CN
  coordinates:
    latitude: '30.8713446'
    longitude: '121.9081413'
  directions: Enter Building 3 and take the stairs to Office on Floor 17
  office_hours:
    - 'Weekdays 09:00 to 17:00'
  appointment_url: 'https://calendly.com/'
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

Welcome!
