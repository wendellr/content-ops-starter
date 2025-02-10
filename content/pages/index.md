---
title: Home
slug: /
sections:
  - type: ImageGallerySection
    subtitle: Nossa Metodologia
    images:
      - type: ImageBlock
        url: /images/livro1liot.png
        altText: Empathy logo
        elementId: ''
      - type: ImageBlock
        url: /images/livro2liot.png
        altText: Wellster logo
        elementId: ''
      - type: ImageBlock
        url: /images/livro3liot.png
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        url: /images/3.png
        altText: Sanity logo
        elementId: ''
      - type: ImageBlock
        altText: Rangle logo
        elementId: ''
    elementId: ''
    motion: static
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    subtitle: Robótica e Internet das Coisas
    text: >
      LioT é uma *startup* que promove o aprendizado por meio da robótica e
      Internet das Coisas, utilizando uma metodologia inovadora, lúdica e
      inclusiva para transformar o ensino em uma experiência acessível e
      inspiradora.
    actions: []
    media:
      url: /images/Design sem nome (17).png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Educação para o futuro
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
    title:
      type: TitleBlock
      text: LioT
      color: text-dark
  - subtitle: Instituições que confiam na gente
    images:
      - url: /images/nepenlogo-pb-peq-2.png
        altText: Wellster logo
        type: ImageBlock
      - altText: Empathy logo
        type: ImageBlock
      - altText: Vise logo
        type: ImageBlock
      - url: /images/ifcelogopbpeq.png
        altText: Telus logo
        type: ImageBlock
      - altText: Contentful logo
        type: ImageBlock
      - altText: Sanity logo
        type: ImageBlock
      - url: /images/LitBrancoPeq2.png
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
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
  - type: GenericSection
    title:
      type: TitleBlock
      text: Ainda estamos cuidando de tudo para ficar bem legal.
      color: text-dark
    subtitle: Mas fique a vontade de nos contactar para trocarmos uma ideia
    text: ''
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Seu nome
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Seu email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Sua mensagem
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Enviar
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
      label: Contacte-nos
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
