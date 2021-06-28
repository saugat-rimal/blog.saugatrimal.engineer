---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Hi there! Thank you so much for your interest in working together. Please
      fill the contact form below or send us an email at
      [mail@saugatreemal.engineer](https://mail.google.com/mail/ca/u/0/?fs=1\&tf=cm\&source=mailto\&to=mail@saugatreemal.engineer).
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Help With Steps in Blogs
          - Projects
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
        is_required: true
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: >+
    I'm always looking for any new opportunities, If you think we could create
    something together!! My inbox is always open so feel free to drop me a
    message.

  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: >+
        I'm always looking for any new opportunities, If you think we could
        create something together!! My inbox is always open so feel free to drop
        me a message.

      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: >+
        I'm always looking for any new opportunities, If you think we could
        create something together!! My inbox is always open so feel free to drop
        me a message.

    - name: 'og:image'
      value: /_static/app-assets/images/contact%20us.jpg
      keyName: property
      relativeUrl: true
layout: advanced
---
