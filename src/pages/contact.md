---
title: ''
hide_title: true
sections:
  - section_id: contact-form
    type: section_form
    content: Keep in touch anytime!
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
    submit_label: Send message to me!
template: advanced
---
