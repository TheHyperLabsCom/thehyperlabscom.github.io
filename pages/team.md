---
layout: list
title: "Team"
description: "Meet our dedicated team."
permalink: "/team/"
date: 2018-02-12T15:37:57+07:00
header_transparent: true

hero:
  enabled: true
  heading: "Our Team"
  sub_heading: ""
  text_color: "#FFFFFF"
  background_color: "#222831"
#  background_gradient: true
#  background_image: "/assets/images/gen/home/bg2.webp"
#  background_image_blend_mode: multiply # "overlay", "multiply", "screen"
  fullscreen_mobile: true
  fullscreen_desktop: true
  buttons:
    enabled: false
    list:
      - text: "Contact Us"
        url: "/contact"
        external: false
        fa_icon: false
        size: large
        outline: true
        style: "light"

grid:
  collection: "team"
  sort_by: "weight" # "date", "weight"
  columns: 3
  prevent_click: false

intro:
  enabled: false
  align: left
  image: false
  heading: "We are a full service digital agency"
  sub_heading: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget sapien in elit semper accumsan. Pellentesque accumsan ut tortor eu varius. Sed id tincidunt massa, ut egestas orci."
  buttons:
    enabled: false
    list:
      - text: "About Us"
        url: "/about/"
        external: false
        fa_icon: false
        size: normal

outro:
  enabled: false
  align: left
  image: false
  heading: "Ready to get started?"
  sub_heading: "Contact us today for a free quote!"
  buttons:
    enabled: true
    list:
      - text: "Get A Quote"
        url: "/contact"
        external: false
        fa_icon: false
        size: normal
---
