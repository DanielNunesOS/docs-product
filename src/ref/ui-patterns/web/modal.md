---
tags: runtime-traditionalweb; 
summary: Advanced use cases for the Modal UI Pattern.
locale: en-us
guid: a9618344-1b9f-4aa8-892b-456d7d7a75eb
app_type: traditional web apps
platform-version: o11
---

# Modal Reference

<div class="info" markdown="1">

Applies only to Traditional Web Apps.

</div>

## Layout and classes

![](<images/modal-5-diag.png>)

## Advanced use case

### Change the animation speed

It is possible to change the animation speed of Modal by using custom CSS. To implement this in your application, copy the CSS to the theme.

```css
.modal .animate {
    -webkit-animation-duration: 500ms;
            animation-duration: 500ms;
}
```
