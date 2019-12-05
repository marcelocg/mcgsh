---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    content: >-
      Here is the place where I write down my latest findings in tech, programming, 
      software architecture, DevOps, gaming and game dev, etc. Maybe you'll see 
      some project ideas and drafts too. It's also one of many places you can find
      me and start a chat.
  - section_id: about
    component: content_block.html
    type: contentblock
    title: About
    content: >-
      I am a software developer since mid 90's and have experienced all major
      languages, platforms and paradigms since. From good old Clipper 5 to 
      VB and Delphi, then some weird ones like Progress and Centura, then to 
      web with ASP and PHP. Well, this was a long time ago...      
      Over the last 20 years (I was about to write "recently", but figured it 
      to not that recent) I've put my hands on Java, Ruby and Python. Had even
      some time and opportunities to experiment with Go, Elixir and Rust. Today
      I'm most focused on backend Java with Spring ecossystem, reactive
      systems, Kafka, Docker and Kubernetes.      
      You can excpect to find content here on any of (but not limited to) these
      ubjects. Hope you like the variety and depth of the articles I write. Feel
      free to get in touch via social media, e-mail or commenting on 
      DEV where my articles are cross-posted.
    actions:
      - label: Contact Me
        url: /contact
  - section_id: recent-posts
    component: posts_block.html
    type: postsblock
    title: Recent Posts
    num_posts_displayed: 4
    actions:
      - label: View Blog
        url: blog/index.html
layout: home
menu:
  main:
    weight: 1
    name: Home
---
