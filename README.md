# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![profile card component](https://profile-ui-component.netlify.app/images/profile-card-component)

### Links

- Solution URL: [GitHub Repository](https://github.com/Sebascode20/profile-card-component)
- Live Site URL: [Profile Card Component Demo](https://profile-ui-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup.
- CSS3.
- CSS Flexbox.
- CSS positioning (relative and absolute).
- CSS background images.
- CSS clip-path.
- CSS border-radius.
- CSS viewport units.
- Google Fonts (Kumbh Sans)
- Mobile-first design principles.

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

During this challenge, I improved my understanding of CSS positioning, Flexbox, background images, and visual styling techniques.

Some of the most important concepts I practiced were:

1. CSS Flexbox

I used Flexbox to organize the main page layout and position the attribution section at the bottom of the viewport.

body {
  min-height: 100dvh;
  display: flex;
  flex-direction: column;
}

.attribution {
  margin-top: auto;
}

2. CSS positioning

I practiced using position: relative and position: absolute to position the profile picture over the card header.

.card__header {
  position: relative;
}

.card__header img {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  margin: 16vh auto;
}

3. CSS clip-path

I learned how to use clip-path to create a circular shape for the profile picture.

.card__header img {
  clip-path: circle(50%);
  border-radius: 50%;
}

4. Multiple background images

I also practiced using multiple background images to recreate the decorative patterns in the page background.

body {
  background-image:
    url("./images/bg-pattern-top.svg"),
    url("./images/bg-pattern-bottom.svg");

  background-repeat: no-repeat;
}

These techniques helped me understand how to recreate visual designs using CSS without relying on external frameworks.

### Continued development

In future projects, I want to continue improving my CSS skills, especially in the following areas:

Responsive web design and media queries.

Advanced CSS selectors.

CSS Grid and Flexbox layouts.

CSS animations and transitions.

Accessibility and semantic HTML.

Writing cleaner and more maintainable CSS code.

I also want to improve my ability to translate design references into accurate and responsive web interfaces.

### Useful resources

- Frontend Mentor - A platform that provides real-world frontend challenges to practice HTML, CSS, and JavaScript.
- MDN Web Docs - CSS - Documentation and examples for learning CSS properties and techniques.
- CSS-Tricks - A Complete Guide to Flexbox - A useful guide to understanding and working with Flexbox.
- Google Fonts - Kumbh Sans - The font family used in this project.

## Author

- GitHub - [@Sebascode20](https://github.com/Sebascode20) 
- Frontend Mentor - [@Sebascode20](https://www.frontendmentor.io/profile/Sebascode20)

## Acknowledgments

Special thanks to Frontend Mentor for providing the challenge and design resources that helped me practice and improve my frontend development skills.
