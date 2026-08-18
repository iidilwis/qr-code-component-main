[README.md](https://github.com/user-attachments/files/31200815/README.md)

# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://iidilwis.github.io/qr-code-component-main/](https://iidilwis.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS box-sizing reset (`border-box`)
- CSS Grid (used to center the card on the page)

### What I learned

**Working from a Figma design for the first time.**
This was my first time building a layout straight from a Figma file instead of just a static image — I really liked it. Being able to inspect exact spacing, font sizes, and colors directly in the design made it much easier to match the result precisely, instead of guessing.

**The most annoying bugs were the smallest ones.**
Most of the mistakes I made weren't about not understanding a concept — they were things like a missing character, a mistyped digit, or a closing tag typed the wrong way. Those are the easiest to make and, somehow, the hardest to spot just by reading the code — I'm learning to double-check the small stuff, not just the logic.

**Spacing with padding.**
I used `padding` on the card and on the text block to keep the layout matching the design, instead of relying only on margins between elements. It made the card feel more like one consistent unit, with consistent breathing room on every side.

```css
.content {
  padding: 16px;
}

.text {
  padding: 0px 16px;
}
```

**A first flirt with CSS Grid.**
I haven't studied Grid properly yet, but I experimented with it anyway to center the card on the page:

```css
body {
  display: grid;
}

.content {
  margin: auto;
}
```

Setting `display: grid` on the body and `margin: auto` on the card centers it both horizontally and vertically, even without defining any explicit rows or columns. It's a small taste of what Grid can do — I'm looking forward to learning it properly and seeing what else it's capable of.

### Continued development

- Responsive/adaptive layout (media queries, flexible units instead of fixed `px`) — deliberately left this for later, once I've studied it properly.
- CSS custom properties (`:root { --color: ... }`) for reusable colors and spacing.
- A "real" CSS Grid layout, with multiple columns/rows, not just single-item centering.
- Flexbox as an alternative approach to layout.

### AI Collaboration

- Used Claude to get a code review of my finished solution.
- Asked it to check my HTML and CSS against the design and style guide, and to point out mistakes as hints rather than ready-made fixes, so I could find and fix them myself first.
- Worked well: having to figure out the fix myself made the lessons stick better than just copying corrected code.

## Author

- Frontend Mentor - [@iidilwis](https://www.frontendmentor.io/profile/iidilwis)
- GitHub - [@iidilwis](https://github.com/iidilwis)
