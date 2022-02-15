---
title: Contact
seo:
  title: Contact
  description: This is the contact page
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
      value: images/mapping-doctrine-of-discovery-favicon.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: About
    - name: 'twitter:description'
      value: This is the about page
    - name: 'twitter:image'
      value: images/mapping-doctrine-of-discovery-favicon.png
      relativeUrl: true
layout: page #advanced enables the YAML form
---
Thank you for your interest in the Doctrine of Discovery Project you can contact us at <info@doctrineofdiscovery.org>


<form name="contactForm-2022" method="POST" action="/thank-you/" data-netlify-honeypot="bot-field" data-netlify="true" id="contact-form" className="contact-form">
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
    <p class="form-row">
        <input id="consent" type="checkbox" name="consent" aria-labelledby="consent-label" required />
        <label for="consent" id="consent-label">I understand that this form is storing my submitted information so I can be contacted.</label>
    </p>
    <input type="hidden" name="form-name" value="contactForm" />
    <p className="form-row form-submit">
        <button type="submit" className="button">Send Message</button>
    </p>
</form>
