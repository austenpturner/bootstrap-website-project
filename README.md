# Bootstrap Website

### Practice project built with bootstrap 5 and SASS based on Patrick Muriung's YouTube tutorial:

[YouTube video](https://www.youtube.com/watch?v=iJKCj8uAHz8&list=PLWKjhJtqVAbmMuZ3saqRIBimAKIMYkt0E&index=11) ||
[Repository](https://github.com/MuriungiPatrick/Bootstrap-5-portfolio-template/tree/main)

### Video of website on large screens, highlighing hover effects and back-to-top button:
![Gif of website on large screens, highlighting hover effects and back to top button](images/screenshots/videos/bootstrapWebsitePracticeLG.gif)

## Changes I made while following along:

* Only using one H1 on the page, and switching to H2 or H3 for sections following the intro
* Moving some of the suggested inline styles to scss files instead as to not use a mixture of inline and imported styles

## Changes I made after following along:

* Navbar:
  * Add margin bottom to phone number button on nav drop down (small and medium screens)
  * Remove bold font weight from nav items
 
* Services section:
  * Add media query for left column border so it only shows up on medium to large screens
  * add d-flex to service containers, change flex-direction to column-reverse on second service so all service text & images are in the same order on small screens, then alternate on large sreens
  * edit services margin and padding
  * make images smaller on small screens
 
* Testimonials:
  * Remove inline styles from horizontal rule, add class, and add styles to scss file instead

* Portfolio:
  * Add cursor: pointer on hover to project images

* Footer:
  * Changing spacing by adding padding, removing margin automatically added by Bootstrap, and center aligning text
  * Making variables for all colors used by added to _custom.scss
  * Remove inline styles and add to scss files instead

## Changes I would make if I continued working on this project:

* Go through and clean up scss files more (i.e., ensure DRY code, reuse styles for headers and hrs)
* Make more mixins, bits or reusable scss
* Make sure all colors have variables (i.e., rgba values)

## What I learned:
* How to customize Bootstrap variables and styles
* How to use Emmet to write HTML quicker
* How to write a script in package.json to compile sass in a specified folder and file:
`
  "scripts": {
    "compile:sass": "sass --watch scss:assets/css"
  }
`
* Practice reading documentation (Boostrap, Font Awesome, GLightbox)
* Existance of helpful resources: [Get Waves](https://getwaves.io/), [Tabler Icons](https://tablericons.com/), [Many Pixels](https://www.manypixels.co/gallery), [GLightbox](https://biati-digital.github.io/glightbox/)

## Why this project?

I've been following along with FreeCodeCamp's [Front End Developer Learning Path](https://www.youtube.com/playlist?list=PLWKjhJtqVAbmMuZ3saqRIBimAKIMYkt0E) video series on YouTube. They are mostly refreshers for me, so I've been going out of order and alternating "easier" and "more difficult" videos. The last one I completed was the 14hr React tutorial. I'm going to skip Tailwind, as I'm feeling very comfortable with Bootstrap and trust I could learn Tailwind from reading the documentation. Next up - Testing!


