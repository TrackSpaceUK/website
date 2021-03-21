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
searchHidden: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page

---
<style>
    .field{
  border: 2px solid grey;
  border-radius: 4px;
}
button{
    font-weight: bold
}
    </style>
Contact us via this form:
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" class = "field" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email"  class = "field" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea  name="message"  class = "field"></textarea></label>
  </p>
  <p>
    <button type="submit" >Submit</button>
  </p>

</form>
