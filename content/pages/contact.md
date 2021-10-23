---
title: Conectar
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |
      ¡Hey! ¡Envíame un mensaje y hablemos!

      O bien, puedes escribirme al correo: yulianarodriguezportilla@gmail.com
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Nombre
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu cuenta de correo electrónico
        is_required: true
      - input_type: select
        name: subject
        label: Título
        options:
          - Saludo
          - Oferta Laboral/Colaboración
          - Otro
      - input_type: textarea
        name: message
        label: Mensage
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información enviada
          para que pueda ser contactado.
    submit_label: Enviar mensaje
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
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
