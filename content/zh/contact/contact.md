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

  email: test@example.org
  phone: 888 888 88 88
  address:
    street: 上海浦东新区海港大道1539号
    # city: 上海
    # region: 浦东新区
    postcode: '201306'
    country: 中国
    country_code: CN
  coordinates:
    latitude: '30.8713446'
    longitude: '121.9081413'
  # directions: Enter Building 3 and take the stairs to Office on Floor 17
  office_hours:
    - '工作日 09:00 至 17:00'
  # appointment_url: 'https://calendly.com/'
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

欢迎联系我们!
