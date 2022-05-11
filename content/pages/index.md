---
title: Home
layout: PageLayout
sections:
  - type: TextSection
    elementId: ''
    colors: colors-f
    title: The Section Title
    subtitle: The section subtitle
    text: >-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt ex
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
  - type: HeroSection
    elementId: ''
    colors: colors-h
    title: Love where you work
    subtitle: ''
    actions:
      - type: Button
        label: Sign Up
        url: /
        style: primary
      - type: Button
        label: Learn More
        url: /
        style: secondary
    media:
      type: ImageBlock
      altText: Hero image
      url: /images/careers.jpg
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
        borderColor: border-primary
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
---
