# freeCodeCamp - Penguin
This is my solution to the Penguin mini-project (https://www.freecodecamp.org/learn)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

- In this project, the challenge was to build a penguin and use CSS transforms to position and resize the parts of the penguin, create a background, and animate the work.

### Screenshot

![](./Penguin.png)

### Links

- Solution URL: (https://github.com/Caius-Scipio/freeCodeCamp/tree/main/ResponsiveWebDesign/Penguin)

## My process

### Built with

- CSS custom properties
- Responsive Design

### What I learned

- My major takeaway from this project was seeing how objects changed as you coded them and sometimes they look odd until you've completed the last line.

Below is some code that I found most interesting or am proud of:

```HTML
<div class="shirt">
    <div>💜</div>
    <p>I CSS</p>
</div>
```

```CSS
@keyframes wave {
    10% {
        transform: rotate(110deg) scaleX(-1);
    }
    20% {
        transform: rotate(130deg) scaleX(-1);
    }
    30% {
        transform: rotate(110deg) scaleX(-1);
    }
    40% {
        transform: rotate(130deg) scaleX(-1);
    }
}
```

### Continued development

- I'm not sure making images with CSS is my forte, but being able to simply animate something on the page is a useful idea I'd like to incorporate into pages as I work on them.