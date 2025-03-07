---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: DEPARTAMENTOS EN PRE-VENTA
      color: text-dark
      type: TitleBlock
    subtitle: Ciudad de Puebla
    text: |
      Un proyecto de residencias modernas.
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
      url: /images/0002_D_V04 copy..jpg
    badge:
      label: BASÂLTICA
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: GenericSection
    title:
      type: TitleBlock
      text: CONTÁCTANOS
      color: text-dark
    subtitle: UN DESARROLLO DE GRUPO JV
    text: |
      Forma parte de la lista exclusiva para recibir la información.
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Nombre
          hideLabel: false
          placeholder: Your name
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: Celular
          label: Celular / Teléfono
          hideLabel: false
          placeholder: Your phone number
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: false
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Comentario
          hideLabel: false
          placeholder: Your message
          width: full
          isRequired: false
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
