---
title: Contact
sections:
  - type: hero_section
    title: Hubungi Saya
    subtitle: >-
      Isi formulir di bawah ini dan saya akan menghubungi Anda dalam 1 hari
      kerja.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ##### harga&#xD;&#xA;Setelah panggilan orientasi singkat, saya akan dapat
      memberi Anda harga rata-rata, diikuti dengan proposal terperinci setelah
      kami membahas detailnya.


      ##### &#xD;&#xA;Usul&#xD;&#xA;Proposal Anda akan mencakup beberapa pilihan
      dalam hal struktur harga dan waktu pengiriman.&#xD;&#xA;Ketentuan


      ##### &#xD;&#xA;Jika suatu saat Anda ingin membatalkan proyek kami, Anda
      harus memberikan pemberitahuan tertulis 30 hari, setelah itu saya akan
      mentransfer semua aset Anda kepada Anda sehingga Anda dapat menggunakannya
      kapan saja.
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
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
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
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
