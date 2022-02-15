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
layout: page #advanced enables the YAML form
---
Thank you for your interest in the Doctrine of Discovery Project you can contact us at info@doctrineofdiscovery.org


<form name="contact" method="POST" netlify-honeypot="bot-field" data-netlify="true">
    <p class="hidden">
        <label> Don’t fill this out if you’re human: <input name="bot-field" /> </label>
    </p>
    <p>
        <label> Email: <input type="text" name="email" /> </label>
    </p>
    <p>
        <label> Message: <textarea name="message"></textarea></label>
    </p>
    <p>
        <button type="submit">Send</button>
    </p>
</form>
