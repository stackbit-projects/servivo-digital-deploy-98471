---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contacto
    content: "Envíanos un mensaje y cuéntanos lo que podemos hacer por ti.\n\n\nTambién puedes llamarnos o enviarnos un WhatsApp:\_[56 1987 8301](https://wa.me/+525619878301)\n"
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información enviada
          para que puedan ser contactados.
        is_required: true
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
