---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/Novo Projeto.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: HeroSection
    title: Bruno
    subtitle: >-
      This is my info—I'm sharing it all this with ya'll to impress you with all
      the hard work I've done in the past few years. Once you're impressed, you
      can continue to scroll down to see more details and credentials about me.
    actions:
      - type: Button
        label: Hire me
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-c
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-36
          - pb-48
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
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-36
          - pb-36
        justifyContent: center
        borderWidth: 1
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: Sobre Mim
    text: >
      `Sou aluno no terceiro ano do Curso de Técnico de Gestão e Programação de
      Sistemas Informáticos na OFICINA - Escola Profissional eu tenho interesse
      em na área de hardware e programação, considero - me dedicado, trabalhador
      e sociável`
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-36
          - pb-36
        justifyContent: center
        borderWidth: 1
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projetos
metaTags:
  - type: MetaTag
    property: 'og:title'
    content: ''
addTitleSuffix: true
---
