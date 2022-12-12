---
date: "2022-10-24"
sections:
 
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: 順天堂大学大学院医学研究科 | 解剖学・生体構造科学講座 協力研究員
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2022-04-01"
      description: |2-
        脊椎動物における喉頭・聴覚器の形態進化
      location: Tokyo
      title: 日本学術振興会特別研究員PD
    - company: 東京大学大学院農学生命科学研究科 | 総合研究博物館 遺体科学研究室 博士課程
      company_logo: org-x
      company_url: ""
      date_end: "2022-03-31"
      date_start: "2019-04-01"
      description: 翼手類の飛行・反響定位器官の進化と発生
      location: Tokyo
      title: 日本学術振興会特別研究員DC1
    title: Experience
  design:
    columns: "2"


- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "4"
    view: citation

- block: contact
  content:
    address:
      city: 
      country: 
      country_code: 
      postcode: "〒113-0033"
      region: 
      street: 東京都文京区本郷2-1-1順天堂大学7号館
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/bio_sonar
      name: Please send DM to me
    email: nojiri0805@gmail.com
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    subtitle: null
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
      ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
