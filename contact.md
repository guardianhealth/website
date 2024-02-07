---
layout: page
title: Contact
subtitle: 
hero_height: is-medium
hero_image: /website/img/guardian-web-home-cover-1.jpg
show_sidebar: false
---

# Test 1
<form accept-charset="UTF-8" action="https://formkeep.com/f/e3a5bffbd98cd60d95d33e99bba58746c" method="POST">
  <input type="email" name="email" placeholder="Your Email">
  <input type="text" name="name" placeholder="Your Name">
  <input type="hidden" name="utf8" value="✓">
  <button type="submit">Submit</button>
</form>

# Test 2 Embed
<div id="formkeep-embed" data-formkeep-url="https://formkeep.com/p/3a5bffbd98cd60d95d33e99bba58746c?embedded=1"></div>

<script type="text/javascript" src="https://pym.nprapps.org/pym.v1.min.js"></script>
<script type="text/javascript" src="https://formkeep-production-herokuapp-com.global.ssl.fastly.net/formkeep-embed.js"></script>

<!-- Get notified when the form is submitted, add your own code below: -->
<script>
const formkeepEmbed = document.querySelector('#formkeep-embed')

formkeepEmbed.addEventListener('formkeep-embed:submitting', _event => {
  console.log('Submitting form...')
})

formkeepEmbed.addEventListener('formkeep-embed:submitted', _event => {
  console.log('Submitted form...')
})
</script>

# Test 3 (action attribute)
<form action="https://formkeep.com/f/287622b7471f"
   accept-charset="UTF-8"
   enctype="multipart/form-data"
   method="POST">


# Test 4
<script src='https://www.google.com/recaptcha/api.js' async defer></script>
<form action="https://formkeep.com/f/287622b7471f"
      accept-charset="UTF-8"
      enctype="multipart/form-data"
      method="POST">
  <input type="hidden" name="utf8" value="✓">

  <label for="email-address">Email Address</label>
  <input type="email" id="email-address" name="email">

  <label for="photo-album">Photos</label>
  <input type="file" id="photo-album" multiple name="photos[]">

  <div class="g-recaptcha" data-sitekey="your_site_key"></div>

  <button type="submit">Submit</button>
</form>
