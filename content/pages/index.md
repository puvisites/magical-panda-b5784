---
title: Landing Page
layout: PageLayout
sections:
  - type: HeroSection
    elementId: ''
    colors: colors-a
    title: ACETECH TOOLS
    subtitle: ''
    badge:
      label: WELCOME TO
      elementId: ''
      styles:
        self:
          textAlign: left
    text: >+
      > We Provide solutions to our customers for their various applications
      with renowned and trusted tools.


      We are the Business associate of SNAPON, GESIPA, SEALEY, FOAM PROGRAM,
      WILLIAMS, SIOUX, BLUE-POINT, BAHCO, who are known for their quality
      product range.

    actions: []
    media:
      type: ImageBlock
      url: /images/Untitled design (8).png
      altText: Hero image
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
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedItemsSection
    colors: colors-f
    elementId: ''
    subtitle: >-
      These are all excellent products that will provide exactly the things
      you’re looking for.
    items:
      - type: FeaturedItem
        elementId: ''
        subtitle: ''
        featuredImage:
          type: ImageBlock
          url: /images/logo.png
          altText: Item image
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        elementId: ''
        subtitle: ''
        featuredImage:
          type: ImageBlock
          url: /images/logo_gesipa.svg
          altText: Item image
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        elementId: ''
        subtitle: ''
        featuredImage:
          type: ImageBlock
          url: /images/snapon.png
          altText: Item image
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        elementId: ''
        subtitle: ''
        featuredImage:
          type: ImageBlock
          url: /images/logo-1ba67e1c.svg
          altText: Item image
        actions: []
        styles:
          self:
            textAlign: left
    actions: []
    columns: 4
    enableHover: false
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
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    title: Our Brands
  - type: ContactSection
    elementId: ''
    colors: colors-h
    backgroundSize: full
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: 'true'
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: 'true'
          width: 1/2
        - type: TextFormControl
          name: address
          label: Home address
          placeholder: Your home address
          isRequired: 'false'
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          isRequired: 'false'
          width: full
        - type: SelectFormControl
          name: city
          label: City
          hideLabel: false
          defaultValue: Please choose...
          options:
            - New York
            - San Francisco
          isRequired: false
          width: full
      submitLabel: Send Message
    media: null
    styles:
      self:
        height: auto
        width: narrow
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
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
