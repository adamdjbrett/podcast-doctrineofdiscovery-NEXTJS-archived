---
title: Contact
seo:
  title: Contact
  description: This is the about page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: About
      keyName: property
    - name: 'og:description'
      value: This is the about page
      keyName: property
    - name: 'og:image'
      value: images/about.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: About
    - name: 'twitter:description'
      value: This is the about page
    - name: 'twitter:image'
      value: images/about.png
      relativeUrl: true
layout: page
---

<form
    name="contactForm"
    method="POST"
    action="/thank-you"
    data-netlify-honeypot="bot-field"
    data-netlify="true"
    id="contact-form"
    className="contact-form"
>
    <p className="screen-reader-text">
        <label>Don't fill this out if you're human: <input name="bot-field" /></label>
    </p>
    <p className="form-row">
        <label htmlFor="contact-form-name" className="form-label">Name</label>
        <input type="text" name="name" id="contact-form-name" className="form-input" />
    </p>
    <p className="form-row">
        <label htmlFor="contant-form-email" className="form-label">Email address</label>
        <input type="email" name="email" id="contant-form-email" className="form-input" />
    </p>
    <p className="form-row">
        <label htmlFor="contant-form-message" className="form-label">Message</label>
        <textarea name="message" id="contant-form-message" className="form-textarea" rows="7" />
    </p>
    <input type="hidden" name="form-name" value="contactForm" />
    <p className="form-row form-submit">
        <button type="submit" className="button">Send Message</button>
    </p>
</form>
