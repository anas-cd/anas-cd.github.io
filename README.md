# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
  - [Develpment path](#Develpment-path)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview
Here is how i approached this challenge 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](media/completed.JPG)



### Links

- Solution URL: [solution URL](https://github.com/anas-cd/stats-preview-card-component)
- Live Site URL: [live site URL](https://anas-cd.github.io/stats-preview-card-component/)

## My process
First the desktop version of the webpage was designed then I moved to the mobile version, since there isn't any tablet size design, I sticked with the desktop version to be the tablet version as well but with more dynamic dimensions

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- scss syntax for css
- gulp for sass compiling
- scss css variables  


### What I learned

Doing this challenge using flexbox made me learn so much more about it, 

one of the aha moments came to me when I saw this trick of making a breaker flexbox to separate the following items to a new line even if the previous item didn't take the full length,  

this is done by adding a breaker element in the html like so : 
```html
<div class="breaker"></div>
```
then css properties : 
```css
.breaker {
  flex: 1 0 100%;
}
```
this simply makes the breaker element takes the entire row forcing the follwing items to break into a new line 


### Useful resources

- [css-tricks:A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understanding how flexboxes work and I'm using it as some kink of cheatsheet.I'd recommend it to anyone still learning this concept
- [tobiasahlin:Breaking to a new row with flexbox](https://tobiasahlin.com/blog/flexbox-break-to-new-row/) - This is an amazing article which helped me finally understand how to break to a new line in flexboxes.

### Development path 
In the following projects I'll try my best to make focus point of the picture on a specific point, for example here it would be better if the focus point of the picture is on the smiling lady
## Author

- Website (still working on it) - [Anas Ali](https://anas-cd.github.io/)
- Frontend Mentor - [@anas-cd](https://www.frontendmentor.io/profile/anas-cd)
- Twitter - [@AnasCd](https://www.twitter.com/AnasCd)


## Acknowledgments

I used a really helpfull and simple boilerplate made by "coder-coder" for frontend development, here is the repo for it : 

- coder-coder - [biolerplate](https://github.com/thecodercoder/frontend-boilerplate)

