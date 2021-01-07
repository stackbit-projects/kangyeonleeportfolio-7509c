---
title: ''
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: Contact to me anytime!
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Your Name
        default_value: ''
        is_required: true
      - input_type: email
        name: mail
        label: Your Email Address
        default_value: ''
        is_required: true
      - input_type: text
        name: subject
        label: Subject
        default_value: ''
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: ''
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send message to me!
template: advanced
---
