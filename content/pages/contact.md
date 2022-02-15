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

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/xbjwognj" method="post">
    <fieldset id="fs-frm-inputs">
        <p class="form-row">
            <label for="full-name">Full Name</label>
            <input type="text" name="name" id="full-name" placeholder="First and Last" required="" />
        </p>

        <p class="form-row">
            <label for="email-address">Email Address</label>
            <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="" />
        </p>

        <div class="g-recaptcha" data-sitekey="6LcJYCoeAAAAAMQIYRE5YiJRi-xCbHsc6ua7v6s4"></div>
        <!-- replace with your recaptcha SITE key not secret key -->
        <p class="form-row">
            <label for="message">Message</label>
            <textarea rows="7" name="message" id="message" placeholder="Note" required="">Your message</textarea>

            <input type="hidden" name="_subject" id="email-subject" value="Doctrine of Discovery Podcast - Contact Form Submission" />
        </p>

        <p class="form-row">
            <input type="checkbox" id="consent" name="consent" aria-labelledby="consent-label" required="" />
            <label for="consent" id="consent-label">I understand that this form is storing my submitted information so I can be contacted.</label>
        </p>
    </fieldset>
    <input type="submit" value="Submit" />
</form>
