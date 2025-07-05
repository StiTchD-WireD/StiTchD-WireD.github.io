# Frontend Mentor - Stats preview card component solution
FIRST ATTEMPT!

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot first attempt Stats Preview Card Component.png]images/Screenshot%20first%20attempt%20Stats%20Preview%20Card%20Component.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: https://stitchd-wired.github.io/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

1. Image: Adding a color overlay to an image, and adjusting hsl, opacity and contrast.
2. Planning and using div classes.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
/* Image*/

.image-column {
  position: relative;
  display: flex;
  justify-items: center;
  align-items: center;
  width: 50%;
  height: fit-content;
  filter: contrast(1.5) brightness(0.8) saturate(0.8);
  overflow: hidden;
  overflow-clip-margin: 20px;
}

/* purple overlay filter*/

.image-column::before {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: hsl(277, 60%, 50%);
  opacity: 0.55;
}
```


### Continued development

Practice positioning and control of images, e.g. using a % to allow for responsive design but not to the negative effect of any neighboring boxes. 
Creating a smoother transition between viewpoints.

### Useful resources

- [W3 Schools](https://www.example.com) - Offers a description of various attributes and functions and allows for testing each one in a small activity.
- [Youtube] - Helped me with the colour overlay on the image. Introduced me to ::before / ::after. 

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)


**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**


_________
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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot first attempt Stats Preview Card Component.png](images/Screenshot%20first%20attempt%20Stats%20Preview%20Card%20Component.png)


Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**





**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)


