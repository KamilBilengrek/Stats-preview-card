# Frontend Mentor - Order summary page solution

## Overview

Hello!  
This is project from the [Frontend Mentor](https://www.frontendmentor.io).  
Different style of website this time. This project required using media queries to make it display properly on all devices. I don't have much experience using media queries but this challenge gave me some idea on how they should be used.

### Links

- Challenge URL: [Here](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62)
- Solution URL: [Here](https://www.frontendmentor.io/solutions/responsive-stats-preview-card-using-flexbox-and-media-query-mNQttfmGY)
- Live Site URL: [Here](https://kamilbilengrek.github.io/Stats-preview-card/)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox
- Media queries

### What I learned

For the first time I used media queries for responsive web design.

```css
/*media queries*/
@media (max-width: 375px) {
    .photo{
        float:right;
        width: 100%;
    }
    .mainFrame{
        display:flex;
        flex-direction: column;
        width:90vw;
    }
    .text{
        width:100%;
        font-size:1em;
        text-align: center;
    }
    .text1{
        padding:1em;
    }
    .text2{
        line-height: 1.5em;
        font-size:1em;
        padding:0 2em 2em 2em;
    }
    .stats{
        flex-direction:column;
        padding-bottom: 2em;
    }
    .oneStat{
        margin:1em;
    }
}
```

### Continued development

In future I want to work on quality of my code as well as starting some java script projects.  
I am also willing to use more media queries to make my websites more accessible.

## Author

- LinkedIn - [Kamil Bilengrek](https://www.linkedin.com/in/kamil-bilengrek-612a82238/)
- GitHub - [KamilBilengrek](https://github.com/KamilBilengrek)
- Frontend Mentor - [Kamil](https://www.frontendmentor.io/profile/Kammilos)

## Contribution

Contribution, issues and feature requests are welcome!

## License

Copyright (c) 2022 Kamil Bilengrek  
This project is [MIT](https://github.com/KamilBilengrek/Order-Summary-page/blob/main/LICENSE.txt) licensed
