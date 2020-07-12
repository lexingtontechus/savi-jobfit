# savijobfitBadge
### An open-source badge to put your mark on every project.

<img src="https://www.savivets.org/wp-content/uploads/2020/07/savijobfit.png" width="600" style="
    margin: 5rem auto;
    display: block;
    border: 4px solid black;
    border-radius: 5px;"/>
    
This project is a fork of MakerBadge - customised for SAVI #jobfit

---

[![Netlify Status](https://api.netlify.com/api/v1/badges/bca76b4b-b052-4950-a678-c0f7738f3861/deploy-status)](https://app.netlify.com/sites/savi-jobfit/deploys)

# How to use SAVI JobFit Badge/MakerBadge:
Use it in 2 steps:

## 1. Get your badge:

```html
<!-- Insert makerbadge.js (download or use ☁️cloud version) -->

<script type="text/javascript" src="https://savi-jobfit.netlify.app/savijobfitbadge.js"></script>

<!-- Initialise MakerBadge with options -->
    
<script>
  savijobfitBadge.init({
       layout:1, 
       theme:'dark', 
       promoText : 'Support Our Veterans '+String.fromCodePoint(0x2192),
       promoLink : 'https://savivets.org/jobfit',
       message : 'Hire A Veteran.',
       title : '#jobfit',
       imageAlt: "SAVI JobFit"
})
</script>
```

## 2. Customise your badge (Beta):

You can customise the values after each colon (e.g. layout:2 - change the 2 to 1)

* layout: a number - 1 (badge with text) or 2 (Round button)
* theme: a string - 'light' or 'dark'.
* promoURL: a string (url) to a donation page.
* message: string - any short message.
* title: string - The title of your badge
* imageAlt: string - Alt text for your image - the default is ""

---

# Contribute

Proudly an open source project.

Feel free to contribute <a target="_blank" href="https://github.com/chriskonings/maker-badge">here</a>
