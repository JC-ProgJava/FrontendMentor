# Frontend Mentor - Space tourism website solution

This is a solution to the [Space tourism website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3).  

## Table of contents
* [Overview](#overview)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My process](#my-process)
  * [Built with](#built-with)
  * [References and Learning Points](#references-and-learning-points)
* [Author](#author)
  * [Note](#note)

## Overview

### Screenshot



### Links

- [Source code](https://github.com/JC-ProgJava/FrontendMentor/tree/master/docs/space-tourism)
- [Web view](https://jc-progjava.github.io/FrontendMentor/space-tourism)

## My process

### Built with

- Raw HTML and CSS

### References and Learning Points

This project was a lot larger than the QR Code Component project, and I enjoyed creating the various
different aspects of the design. As this project was designated `Free+`, I was able to view the Figma
design file, which helped with the implementation.

Something I experimented with during this project was the use of dynamic font sizes through the use of
CSS unit `vw`, which represents a percentage (%) of the viewport width. 

I also learned about (or refreshed my understanding of) various other CSS attributes, including:

- `text-transform: uppercase;` - sets text to full uppercase.
- `font-variant: normal | small-caps;` - sets font variant.
- `cursor: pointer` - changes cursor to pointer.
- `box-shadow: inset | offset-x | offset-y | color;` - creates box shadow with various properties.
- `letter-spacing` - sets spacing between characters.
- `box-sizing: border-box;` - calculates widths of elements by including element width, padding, borders
- `display: flex;`
- `justify-content: space-between;` - works in sync with `display: flex` to justify elements with space between.
- `position: fixed | sticky;` - I learned the difference between sticky and fixed positions. 
Sticky positions essentially only fix elements once reaching a particular spot. It 'sticks' its position relatively
to another element.
- `object-fit: cover;` - prevents image distortion (keep same aspect ratio) after resizing.

I also used other CSS features like `@import` and `@media` to import fonts and control 
viewport styling respectively.

Some particularly notable aspects of the project are the implementation of hover states. I decided to
create all effects using `box-shadow` and it suited the use case better than `border`.

## Author

- [JC-ProgJava](https://github.com/JC-ProgJava)
- Frontend Mentor - [Frontend Mentor @JC-ProgJava](https://www.frontendmentor.io/profile/JC-ProgJava)

### Note

- Figma design file provided as project is designated `Free+`.