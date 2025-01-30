# marp-dlr-theme

Unofficial Marp DLR theme.

URL to use this theme:

`https://raw.githubusercontent.com/joh-lin/marp-dlr-theme/refs/heads/main/dlr.css`

Supports following syntax:

## Columns
```md
---

<div class="columns">
<div class="col">

    - first column

</div><div class="col">

    - second column

</div></div>

---
```

## Title Slide
```md
---

<!-- _class: title -->
# Big title
## Subtitle
#
Author

---
```

## Chapter
Same as title but
`<!-- _class: chapter -->`

## Additions
```md
---

<div class="additions">

    - This will render at the bottom
    - Just like in dlr template
    - with blue background

</div>

---
```

## Styling
```css
<style>
:root {
    font-family: Arial, Helvetica, sans-serif;
    --accent-color: rgb(); /* color of border and accent */
    --subheading-bg-color: rgba(); /* background color of subheading and additions banner */
    --title-bg-tint: rgb(57, 140, 201); /* tint overlay for title and chapter background */
    --left-border-width: 35px; /* standart width of left border */
    --title-bg-image: url(); /* title background image */
    --company-logo: url(); /* url to dlr logo */
    --title-size: 1.9em;    /* size of h1 on title page */
    --chapter-title-size: 1.9em; /* size of h1 on chapter page */
}
section.title {
    --left-border-width: 70px; /* change left border with for title page */
}
</style>
```