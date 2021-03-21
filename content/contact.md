---
title: "Contact"
# weight: 1
# aliases: ["/first"]
author: "Lucas Sycamore"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
draft: false
hidemeta: true
comments: false
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
searchHidden: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page

---

Contact us via this form:

<!DOCTYPE HTML>
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit" class = "btn btn-sm btn-outline-dark tag-btn" >Submit</button>
  </p>
</form>