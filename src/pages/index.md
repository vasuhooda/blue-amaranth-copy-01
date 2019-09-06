---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: HeroBlock
  content: 'I do science. This is some text. '
  title: 'I''m Damanveer '
  actions: []
- type: contentblock
  template: contentblock
  title: About
  section_id: about
  actions:
  - label: Contact Me
    url: "/contact"
  component: ContentBlock
  content: I use high pressure-temperature experiments to constrain the effect of
    core formation on the origin of major volatiles (carbon, nitrogen, sulfur and
    water) in rocky bodies in the inner Solar System. These constraints can help build
    up a framework to better understand the accretion and differentiation processes
    operational in the early Solar System.
  image: "/images/Daman_Grewal.jpeg"
- type: postsblock
  template: postsblock
  title: Recent Posts
  section_id: recent-posts
  actions:
  - label: View Blog
    url: blog/index.html
  component: PostsBlock
  num_posts_displayed: 4
menus:
  main:
    title: Home
    weight: 1
template: home

---
