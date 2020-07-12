# BLMBadge
### An open-source badge to put your mark on every project.

<img src="https://www.savivets.org/wp-content/uploads/2020/07/savijobfit.png" width="600" style="
    margin: 5rem auto;
    display: block;
    border: 4px solid black;
    border-radius: 5px;"/>
    
This project is a fork of MakerBadge - customised for SAVI #jobfit

---

# How to use SAVI JobFit Badge/MakerBadge:
Use it in 2 steps:

## 1. Get your badge:

```html
<!-- Insert makerbadge.js (download or use ☁️cloud version) -->

<script type="text/javascript" src="https://makerbadge.s3.amazonaws.com/blmbadge.js"></script>

<!-- Initialise MakerBadge with options -->
    
<script>
  savijobfitBadge.init({
       layout:1, 
       theme:'dark', 
       promoText : 'Hire Our Veterans '+String.fromCodePoint(0x2192),
       promoLink : 'https://savivets.org/jobfit',
       message : 'Hire Our Veterans.',
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
* imageAlt: string - Alt text for your image - the default is "Black Lives Matter Badge"

---

# Contribute

Proudly an open source project.

Feel free to contribute <a target="_blank" href="https://github.com/chriskonings/maker-badge">here</a>
