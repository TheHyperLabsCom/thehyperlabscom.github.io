---
layout: home
permalink: "/"
title: "World's First Bitcoin Developers"
description: "Those who build on Bitcoin, sculpt the currency of the future. We are the builders."
header_transparent: true
meta_title: The Hyperlabs

hero:
  enabled: true
  heading: "World's First Bitcoin Developers"
  sub_heading: "Those who build on Bitcoin,</br>sculpt the currency of the future. <br/> Join us."
  text_color: "#FFFFFF"
  show_svg_map: true
#  background_gradient: true
  #background_image: "/assets/images/gen/home/bg2.webp"
  background_image_blend_mode: multiply # "overlay", "multiply", "screen"
  fullscreen_mobile: true
  fullscreen_desktop: true
#  height: "500px"
  buttons:
    enabled: true
    list:
      - text: "Contact Us"
        url: "/contact"
        external: false
        fa_icon: false
        size: large # "small", "normal", "large"
        outline: false
        style: "light" # "light", "dark", "primary"
      - text: "About us"
        url: "/about"
        external: false
        fa_icon: false
        size: large
        outline: true
        style: "light"

services:
  enabled: true
  heading: "Our Services"
  sub_heading: ""
  limit: 6
  sort: "weight" # 'date'
  view_more_button_text: "View All Services"
  view_more_button_link: "/services"
  prevent_click: false

intro:
  enabled: false
  align: left
  image: "/assets/images/gen/content/content-5-thumbnail.webp"
  heading: "We've helped hundreds of people grow their business online."
  sub_heading: "Our software empowers customers and retailers to work from anywhere in the world, on the go, or at home."
  features:
    enabled: false
    list:
      - text: "Configure the homepage sections in front-matter."
        fa_icon: "fas fa-check"
      - text: "An advanced hero image section with dozens of design options."
        fa_icon: "fas fa-check"
      - text: "Fully responsive and SEO optimised."
        fa_icon: "fas fa-check"
      - text: "Multiple content types including services, projects, blog and more."
        fa_icon: "fas fa-check"
  buttons:
    enabled: true
    list:
      - text: "About Us"
        url: "/about"
        external: false
        fa_icon: ""
        size: large
        outline: false
        style: "primary"

partners:
  enabled: true
  limit: 2
  sort: "weight" # 'date'

projects:
  enabled: true
  heading: "Our Projects"
  sub_heading: ""
  limit: 7
  columns: 2
  sort: "weight" # 'date'
  view_more_button_text: "View All Projects"
  view_more_button_link: "/projects"
  prevent_click: false

outro:
  enabled: true
  align: center
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
        size: "normal"
        outline: false
        style: "light"

posts:
  enabled: false
  heading: "Latest Posts"
  sub_heading: ""
  limit: 3
  columns: 3
  sort: "weight" # 'date'
  view_more_button_text: "View All Posts"
  view_more_button_link: "/blog"
  prevent_click: false
---
