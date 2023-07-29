# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.   

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![](https://lh3.googleusercontent.com/fife/AKsag4Num3-nqbS733hiD449rE1pTvzOYbR9SfBEqE86YUlQmFvPT71qdrdNqAj7eyZYruFKlKmQkVY2XQ_Mk-FQNKU8q-8FtNw1p-hD-sxi5fX_KhJjUVuiw8GDu_QnNHzyNr1K-y0Uw8nHgxZLvszrVzVZSyOfW8MZlHm4T9P1PS4bI1zHxNBjyd_M1flvzUU0Q00bLw5OE68DkvKjG3-xncm7KG0vfvA-9wOnv3sOWELv4UoaTuKjfmz0HphrEGD4TdGEJ4hfmBG-F12YvmHkikSozkAeeFRyuWTcGcQXE1BwyYVZv69km4aQhmoF2MzHaRvcl6bfsIrjwybPMgFTDsNRPNfjzrMatJ8wNRioXFIFZPMlGTd-Ik67E8rT4t7PNVW33Jf2iqiC5qYeKkAtlPMZ98CY7MUlUTPAJG3gJRXOSBR-4_uKDAECOIGPfueWOso85LKzguLxd-YeUfGOrgGjJEl6vPua9SdhH8-nthSV7yloqL5Ggdh0E0oFnI7B-MtV-K8jC2fOOGeMqUkf-ll64lOb5ZMnySThguuMRLc_Bo7Bw_aqP3JN8z0BiRImQKLELHiVVJdOdTDkSWU9c41-nCb__FZBzMr3V73Oof4NF_JGxAmPLLauyQysNjt9W5BbQh58aMbL2ayhvCy1wTp3dqbbpIlImt28pvO4bSgD7f_HbufXok5WmfnuTr02e2qMQnTq3BCtF5niMHJPbwdszkYufGUGKYKjHkC-qhs8BFxQNcONhKCgZigo-Z_XKgNUMPTLktSYFVKddXYptCAuWsBq5Iq5QloVWfCCzbrQtduT3dwVbKv7YaIZAx1yO40lCqBNT-on1zC3h2Y2ztrOAcBHowCbB17xe8uRypso4Cjm5yPAq0Y9JSUuOH-jfpymdY-l3luJZkCtcFHSRsDmiwbmm0BpjKP_Q5pjS4NTBea4B9Q_2F19ohkTjE174IdErnkuVtPgXTberNSpGqPt2okfPrFVmknlIu_d6ZEtcLa_O3aRskkW_PQ1Vo9m4j8Ul9sfNyhNef7Wn9Cy58tCD6jCGxij9aJKCehlDiu3YO7iAez17hiTJ7jjnenGjffpmP7wFnIZryhcFgkuqPa2fHUChgqb5bdHzO4syaTgkU0J3AvxS34uIL0r4fzvo8QEMt0b1QPVTZT-dCqSqo9xhs3DfJyySt4kgTmQ2bidy2xFPxWTPoJpE1hjcnoaDbFMWSZUtKDgO7KRPH_OX3hOJwmSDM3SnkUUQRbDMM761ypf1JuTj0bo6_uk4paz477Fzcfc5mQO2lsxr6VOY0y2mt2IDouHSOy3zqRRlipZonSxWo2DuYV2ugUjZ_20oygcXiS2KQJFsWAtNnrSpPC3X44YJUAljTG0iaqmX9MkOK2m1m1zEHL9M6V2oM-rvHV6ADl9h2mPUFxuvsyep-Ok6cpkEnduMW0yhmUAYPQc4IdrFemoXjhLsgGFzin6KDmK5ax5YP8CSafdYTLrN7Vdr4zj0Wa3WHESAEZxQv98lawcgdizYr2ggvC03Rxco6ktZQ=w1920-h923)

### Links

- Solution URL: [Source Code](https://github.com/andrearecuyo/faq-accordion-card-main)
- Live Site URL: [Demo](https://andrearecuyo.github.io/faq-accordion-card-main/)

## My process

### Built with

- HTML
- CSS
- JavaScript
- Flexbox
- [LESS](https://lesscss.org/) - For styles

### What I learned
I learned how to implement details and summary elements, I used these elements to create an accordion-like behavior to show/hide the answer to each question. Also, I learned how to use position: absolute and clip-path to position and clip the illustration elements.
 
 ```html
<details>
  <summary>
    How many team members can I invite?
    <img class="icon" src="./images/icon-arrow-down.svg" alt="">
  </summary>
  <p>You can invite up to 2 additional users on the Free plan. There is no limit on team members for the Premium plan.</p>
</details>

```
### Useful resources

- [HTML <summary> Tag](https://www.w3schools.com/tags/tag_summary.asp) - This helped me implement accordion without the use of JavaScript.
- [clip-path](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path) - This helped me create a clipping region of the background images for desktop version.


## Author

- Website - [Andrea Recuyo](https://andrearecuyo.github.io/andrearecuyoportfolio/)
- Frontend Mentor - [@andrearecuyo](https://www.frontendmentor.io/profile/andrearecuyo)

## Acknowledgments

Thank you to Frontend Mentor for providing frontend challenges.