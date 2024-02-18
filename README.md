# Frontend Mentor - Recipe page

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

## Table of contents

- [Frontend Mentor - Recipe page](#frontend-mentor---recipe-page)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)


## Overview

The challenge is to build out this recipe page and get it looking as close to the [design](/design/desktop-design.jpg) as possible.

### Screenshot

**Desktop View**
![](/screenshot/desktop.png)

**Mobile View**

![](/screenshot/mobile.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/recipe-page-solution-mobile-responsive-q1Nbfe65Fn)
- [Live Site URL](https://recipe-page-v1.netlify.app/)

### Built with

- HTML & CSS

### What I learned

I learned to adjust space between list style (bullet or decimal) and list text.

```css
ul, ol {
    li {
      list-style-position: outside;
      padding: 0 20px;
      margin-top: 12px;
      margin-left: 20px;

      &::marker {
        color: var(--nutmeg);
      }
    }
  }
```

### Useful resources

- [CSS: Control space between bullet and list text](https://stackoverflow.com/questions/4373046/css-control-space-between-bullet-and-li)


## Author

- Website - [Akash Banchhor](https://akashbanchhor.netlify.app)
- Frontend Mentor - [@akash02ab](https://www.frontendmentor.io/profile/akash02ab)
