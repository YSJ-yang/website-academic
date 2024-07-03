---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
    design:
      columns: '2'
  - block: collection
    id: working_papers
    content:
      title: Working papers
      count: 0
      # text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - working_papers
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: publications
  #   content:
  #     title: Publications
  #     count: 0
  #     # text: |-
  #     #  {{% callout note %}}
  #     #  Quickly discover relevant content by [filtering publications](./publication/).
  #     #  {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  - block: markdown
    id: teaching
    content:
      title: Teaching
      autolink: true
      text: |-
        Lorem ipsum dolor sit amet, <a href="/uploads/bellman_xyl.pdf">consectetur</a> adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim. 
        <ul><li>aaa</li><li>bbb</li></ul>
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
     # text: |-
     #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: xiaoyangli@uchicago.edu
      # appointment_url: 'https://calendly.com'
      address:
        street: University of Chicago, 5757 S University Ave
        city: Chicago
        region: IL
        postcode: '60637'
        country: United States
        country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---
