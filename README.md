# html-css-project-boilerplate
# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Project Description](#project-description)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

Clipboard landing page is a webpage including various elements i.e. images, buttons, links etc. To make this webpage, HTML, CSS is used. This project mainly focuses on implementation of header, main, section, div, img, ul, li, footer tag of HTML and CSS layout and responsive web design elements. 

Website is divided into header, menu, content and footer. There are some active elements over which hover properties is defined.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page


### Project Description
a. I chose this project as I have put my layout skills to the test with this HTML & CSS landing page challenge. This project includes a design for hover states. This project also solves responsiveness of website on mobile as well as desktop. 

The CSS Grid is useful for designing websites. with the help of it we can divide the whole body of the webpage into different sub segments and also we can overlap one segment upon another as desired. It can be considered as an alternative to bootstrap Grid.

Media query is used to make webpage responsive by adding a breakpoint according to different screen sizes. It is a CSS technique introduced in CSS3. It uses the @media rule to include a block of CSS properties only if a certain condition is true.

b. I have used HTML and CSS to build this website.

c. I had implemented some of the featues including;-
   - making website responsive on multiple device screens.
   - css grid is used for designing the website layout.
   - css media queries is used to make the page responsive on multiple devices.


### Links

- Live Site URL: [Netlify](https://jatin-clipboard-landing-page.netlify.app/)

## My process

- In html at first I wrote different sections including header, content and footer. In content I have written different sections one after the other. Some sections include image as well. 
The main elements it have:- 
<!DOCTYPE html>
<html lang="en">
<head>
  ........
</head>

<body>
  <header>
    .........
  </header>

  <main>
    ........
  </main>

  <footer>
    ........
  </footer>
</body>
</html>

- Then in the stylesheet the background and the page layout structures are set using background and color padding and margin properties.
- CSS properties I have used are width, margin, padding, display, media queries, hover, color, background, align, border etc.
- Respective page background are applied as in hsl color scheme format.
- For span of the differnt sections grid-template-columns and box-sizing, border-box property is used.
- For responsiveness media query is used.
- Font family and card colors used as per the specification mentioned below in the Style specification.

# Front-end Style Guide

    ## Layout

    The designs were created to the following widths:

    - Mobile: 375px
    - Desktop: 1440px

    ## Colors

    ### Primary

    - Strong Cyan: hsl(171, 66%, 44%)
    - Light Blue: hsl(233, 100%, 69%)

    ### Neutral

    - Dark Grayish Blue: hsl(210, 10%, 33%)
    - Grayish Blue: hsl(201, 11%, 66%)

    ## Typography

    ### Body Copy

    - Font size: 18px

    ### Fonts

    - Family: [Bai Jamjuree](https://fonts.google.com/specimen/Bai+Jamjuree)
    - Weights: 400, 600


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media queries for responsiveness

### What I learned

I have learnt the best practice to write html code using header, main, and footer, sections and div tag in main, use of span tag. Use of div tag to divide different sections of web page.

In CSS, I learnt mostly to build a perfect layout using css grid, box sizing property, use of margin and padding to align html elements and use of media queries to make page responsive.

To see how you can add code snippets, see below:

```html
<section class="two">
      <img src="images/image-computer.png" alt="/images/image-computer.png">
      <div class="features">
        <div>
          <h3>Quick Search</h3>
          <span>Easily search your snippets by content, category, web address, application, and more.</span>
        </div>
        <div class="features">
          <h3>iCloud Sync</h3>
          <span>Instantly saves and syncs snippets across all your devices.</span>
        </div>
        <div class="features">
          <h3>Complete History</h3>
          <span>Retrieve any snippets from the first moment you started using the app.</span>
        </div>
      </div>
  </section>
```
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* for mobile screens*/
@media (max-width: 765px){

}
```


### Continued development

- CSS flexbox is layout module, I can learn it better by applying it in more projects. 
- I learnt layout and CSS grid use to make layout easily according to need, I will explore more onto it.
- media queries was very new to implement, now I will implement it for various device screens in future projects.


### Useful resources

- [W3schools](https://www.w3schools.com/css/css_website_layout.asp) - This helped me for implementation of css grid, flexbox, padding, margin, width and box-sizing concept. I really liked this pattern and will use it going forward.
- [W3schools](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This is an amazing article which helped me finally understand media queries impelmentation to provide responsiveness for different screens. I'd recommend it to anyone still learning this concept.


## Author

- Author Name - Jatin Mangal
- LinkedIn - [@jatin-mangal-184972a7](https://www.linkedin.com/in/jatin-mangal-184972a7/)

