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
        name: liame
        label: Email
        default_value: ''
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
template: advanced
---
