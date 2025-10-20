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
  # - block: collection
  #   id: working_papers
  #   content:
  #     title: Working papers
  #     count: 0
  #     # text: |-
  #     #  {{% callout note %}}
  #     #  Quickly discover relevant content by [filtering publications](./publication/).
  #     #  {{% /callout %}}
  #     filters:
  #       folders:
  #         - working_papers
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  - block: markdown
    id: working
    content:
      title: Working Papers
      autolink: true
      text: |-
        Xiaoyang Li (2024). <a href="https://xiaoyangli.com/uploads/li_shakeouts_innovation.pdf">Industry Shakeouts after an Innovation Breakthrough</a>.   [<a href="https://xiaoyangli.com/uploads/li_shakeouts_innovation_slides.pdf">Slides</a>] <a href=# class="btn btn-outline-primary btn-page-header btn-sm js-cite-modal" data-filename=/working_papers/shakeouts/cite.bib>Cite</a>
        <p>
        Xiaoyang Li, Shijian Yang, and Wei Lin (2024). <a href="https://xiaoyangli.com/uploads/li-yang-lin_land.pdf">Much ado about Property Rights: China’s Agricultural Wedges</a>. <a href=# class="btn btn-outline-primary btn-page-header btn-sm js-cite-modal" data-filename=/working_papers/chinalandproject/cite.bib>Cite</a>
    design:
      columns: '2'
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
        <b>University of Chicago (TA)</b> 
        <ul>
          <li> Microeconomics II (PhD) for Lars Stole</li>
          <li> Microeconomics III (PhD) for Phil Reny</li>
          <li> Macroeconomics II (Undergraduate) for Sergio Salas </li>
        <b> Booth School of Business , University of Chicago (TA)</b>
         <ul>
          <li>Microeconomics (Executive MBA) for Lars Stole</li>
          <li>Competitive Strategy (Executive MBA) for Luis Garicano</li>
        </ul>       
    design:
      columns: '2'
#  - block: contact
#    id: contact
#    content:
#      title: Contact
#      subtitle:
     # text: |-
     #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
#      email: shijianyang@uchicago.edu
      # appointment_url: 'https://calendly.com'
#      address:
#        street: <a target="_blank" href="https://www.google.com/maps/place/Saieh+Hall+For+Economics/@41.7898742,-87.5997978,17z/data=!3m2!4b1!5s0x880e291673e1b1eb:0x92cc235cda05dc67!4m6!3m5!1s0x880e29167109ab39:0xb987695b29fdfeb4!8m2!3d41.7898702!4d-87.5972229!16s%2Fg%2F11b6sd2v87?entry=ttu">Saieh Hall, 5757 S University Ave</a>
#        city: Chicago
#        region: IL
#        postcode: '60637'
#        country: United States
#        country_code: US
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
#      autolink: true
      # Email form provider
      # form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
#    design:
#      columns: '2'
---
